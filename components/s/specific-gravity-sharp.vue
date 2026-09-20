<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq-doe4nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:specific-gravity-sharp" /></template>
<style>
.mq-doe4nz {
  fill: currentColor;
  d: path("M6.104 21L4.116 3h15.769l-1.989 18zM5.733 8.5h3.829q.467-.475 1.093-.737Q11.281 7.5 12 7.5t1.345.263t1.094.737h3.828L18.75 4H5.225zm6.27 5q1.034 0 1.765-.735t.732-1.769t-.735-1.764t-1.769-.732t-1.764.736t-.732 1.768t.736 1.764t1.768.732");
}

</style>
