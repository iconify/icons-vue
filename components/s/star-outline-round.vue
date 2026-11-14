<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y25ob5beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:star-outline-round" /></template>
<style>
.y25ob5beo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.831 6.121l.725 2.014q.228.635.902.661l2.071.08q1.348.052 1.755 1.338t-.666 2.103l-1.68 1.281q-.562.428-.347 1.1l.623 1.949q.409 1.276-.665 2.078t-2.182.047l-1.804-1.23q-.563-.385-1.126 0l-1.803 1.23q-1.108.754-2.183-.047q-1.074-.802-.665-2.078l.623-1.948q.215-.673-.347-1.101l-1.68-1.28q-1.072-.818-.666-2.104t1.755-1.338l2.071-.08q.674-.026.902-.661l.725-2.014Q10.633 4.835 12 4.835t1.83 1.285z");
}

</style>
