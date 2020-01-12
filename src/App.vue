<script>
export default {
  data () {
    return {
      title: 'My portfolio'
    }
  },
  mounted () {
    const $ = this.jquery
    this.$nextTick(() => {
      // our custom jQuery code goes here
    })
  }
}
</script>