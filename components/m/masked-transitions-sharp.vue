<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xapybybzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:masked-transitions-sharp" /></template>
<style>
.xapybybzr {
  fill: currentColor;
  d: path("M5.137 18.864q-1.752-1.753-1.752-4.249t1.752-4.248t4.248-1.752t4.248 1.752t1.752 4.248t-1.752 4.248t-4.248 1.752t-4.248-1.752m7.785-.71q1.463-1.463 1.463-3.537t-1.463-3.538t-3.537-1.463t-3.538 1.463t-1.462 3.538t1.462 3.537t3.538 1.463t3.537-1.463m3.836-3.184q.011-.092.011-.171v-.183q0-3.056-2.164-5.22t-5.22-2.164h-.183q-.079 0-.171.011q.496-1.469 1.982-2.663t3.603-1.195q2.496 0 4.248 1.752t1.752 4.248q0 2.118-1.195 3.603t-2.663 1.982");
}

</style>
