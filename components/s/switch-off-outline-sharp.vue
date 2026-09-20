<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9l4q2n5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-off-outline-sharp" /></template>
<style>
.r9l4q2n5p {
  fill: currentColor;
  d: path("M4.98 21V3H19v18zm1-1H18V4H5.98zm2.732-3.73h6.577V7.711H8.71zm5.577-7.558v4.672H9.712V8.712zM11.98 18.807q.292 0 .482-.201t.19-.469q0-.29-.188-.493q-.19-.203-.479-.203q-.267 0-.472.203q-.206.203-.206.493q0 .268.202.469t.47.2m0-12.288q.293 0 .483-.2q.19-.202.19-.47q0-.29-.188-.483q-.19-.193-.479-.193q-.267 0-.472.193q-.206.193-.206.488q0 .273.202.469t.47.196m0 5.481");
}

</style>
