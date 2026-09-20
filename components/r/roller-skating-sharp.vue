<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs0ifzbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:roller-skating-sharp" /></template>
<style>
.fs0ifzbzm {
  fill: currentColor;
  d: path("M4.5 15.5v-14h7.308v2.616H9.116v.769h2.692v.62q0 .156.012.311t.057.3H9.116v.769h3.033q.313.575.83.975t1.169.6l5.16 1.428V15.5zm-1.27 6.272q-.73-.729-.73-1.77t.729-1.771t1.769-.731t1.771.729t.731 1.769t-.728 1.771t-1.77.731t-1.771-.728m15.771.728q-1.04 0-1.771-.728t-.731-1.77t.729-1.771t1.769-.731t1.771.729t.731 1.769t-.728 1.771t-1.77.731m-7 0q-1.04 0-1.771-.728t-.731-1.77t.729-1.771t1.769-.731t1.771.729t.731 1.769t-.728 1.771t-1.77.731");
}

</style>
