<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="s8v0l0bbn"/><path class="xrcoiubve"/><path class="wj398dbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:sparkles" /></template>
<style>
.s8v0l0bbn {
  fill: var(--svg-color--f4ba37, #f4ba37);
  d: path("m14.401 45.2l-3.768-8.722L6.866 45.2l-6.891 4.77l6.891 4.771l3.767 8.721l3.768-8.721l6.891-4.771zM13 53.23l-2.368 5.475l-2.367-5.475l-4.325-2.995l4.325-2.998l2.367-5.475L13 47.237l4.325 2.998z");
}

.wj398dbsm {
  fill: var(--svg-color--29abe2, #29abe2);
  d: path("m13.495 10.8l-2.249-5.203L9 10.8l-4.109 2.846L9 16.492l2.247 5.202l2.249-5.202l4.111-2.845zm-.989 4.44l-1.259 2.916l-1.26-2.916l-2.303-1.594l2.303-1.596l1.259-2.914l1.259 2.914l2.305 1.596z");
}

.xrcoiubve {
  fill: var(--svg-color--d94c9a, #d94c9a);
  d: path("M48.824 19.779L40.509.538l-8.311 19.241l-15.205 10.522l15.205 10.525l8.311 19.239l8.315-19.239l15.201-10.525zm-3.091 17.716l-5.225 12.08l-5.223-12.08l-9.541-6.608l9.541-6.611l5.223-12.08l5.225 12.08l9.54 6.611z");
}

</style>
