<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbvcm9brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:masked-transitions-add-rounded" /></template>
<style>
.wbvcm9brt {
  fill: currentColor;
  d: path("M8.885 17.5v-2.384H6.5v-1h2.385V11.73h1v2.385h2.384v1H9.884V17.5zm-3.748 1.364q-1.752-1.752-1.752-4.248t1.752-4.249t4.248-1.752t4.248 1.752t1.752 4.249q0 2.496-1.752 4.248t-4.248 1.752t-4.248-1.752m7.785-.711q1.463-1.462 1.463-3.537t-1.463-3.538t-3.537-1.462t-3.538 1.462t-1.462 3.538t1.462 3.537t3.538 1.463t3.537-1.463m3.836-3.184q.011-.092.011-.171v-.182q0-3.056-2.164-5.22Q12.44 7.23 9.385 7.23h-.183q-.079 0-.171.011q.496-1.469 1.982-2.663t3.603-1.194q2.496 0 4.248 1.752t1.752 4.248q0 2.117-1.195 3.603t-2.663 1.981");
}

</style>
