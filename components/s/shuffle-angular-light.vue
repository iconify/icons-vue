<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oxqthmbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:shuffle-angular-light" /></template>
<style>
.oxqthmbol {
  fill: currentColor;
  d: path("M236.24 179.76a6 6 0 0 1 0 8.48l-24 24a6 6 0 0 1-8.48-8.48L217.52 190H168a6 6 0 0 1-4.88-2.51L84.91 78H32a6 6 0 0 1 0-12h56a6 6 0 0 1 4.88 2.51L171.09 178h46.43l-13.76-13.76a6 6 0 0 1 8.48-8.48Zm-92.07-74.4a6 6 0 0 0 8.37-1.4l18.55-26h46.43l-13.76 13.8a6 6 0 1 0 8.48 8.48l24-24a6 6 0 0 0 0-8.48l-24-24a6 6 0 0 0-8.48 8.48L217.52 66H168a6 6 0 0 0-4.88 2.51L142.78 97a6 6 0 0 0 1.39 8.36m-32.34 45.28a6 6 0 0 0-8.37 1.4L84.91 178H32a6 6 0 0 0 0 12h56a6 6 0 0 0 4.88-2.51L113.22 159a6 6 0 0 0-1.39-8.36");
}

</style>
