<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7duhr1tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:roller-skating" /></template>
<style>
.n7duhr1tj {
  fill: currentColor;
  d: path("M4.5 15.5v-14h7.308v2.616H9.5q-.154 0-.27.115q-.114.115-.114.269t.115.27q.115.114.269.114h2.31v.621q0 .156.011.311q.012.155.056.3H9.5q-.154 0-.27.115q-.114.115-.114.269t.115.27q.115.114.269.114h2.643q.318.575.837.975t1.168.6l2.625.725q1.146.293 1.84 1.226t.695 2.119V15.5zm-1.27 6.272q-.73-.729-.73-1.77t.729-1.771t1.769-.731t1.771.729t.731 1.769t-.728 1.771t-1.77.731t-1.771-.728m15.771.728q-1.04 0-1.771-.728t-.731-1.77t.729-1.771t1.769-.731t1.771.729t.731 1.769t-.728 1.771t-1.77.731m-7 0q-1.04 0-1.771-.728t-.731-1.77t.729-1.771t1.769-.731t1.771.729t.731 1.769t-.728 1.771t-1.77.731");
}

</style>
