<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvwwxpbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:reset-colors-sharp" /></template>
<style>
.rvwwxpbnv {
  fill: currentColor;
  d: path("m17.5 23.6l-6.1-6.1l4.7-4.7l-1.95-1.95l1.4-1.4l8.075 8.05zm-3.3-6.1h6.6l-3.3-3.3zM4 21v-2h2.35Q4.8 17.75 3.9 15.938T3 12q0-1.875.713-3.512t1.924-2.85t2.85-1.925T12 3q3.225 0 5.663 1.988T20.775 10H18.7q-.65-2.2-2.475-3.6T12 5Q9.075 5 7.038 7.038T5 12q0 1.8.813 3.3T8 17.75V15h2v6z");
}

</style>
