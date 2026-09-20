<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmp2z3byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-off-sharp" /></template>
<style>
.dmp2z3byd {
  fill: currentColor;
  d: path("M4.98 21V3H19v18zm3.732-4.73h6.577V7.711H8.71zm5.577-7.558v4.672H9.712V8.712zM11.98 19.307q.292 0 .482-.201t.19-.469q0-.29-.188-.493q-.19-.203-.479-.203q-.267 0-.472.203q-.206.203-.206.493q0 .268.202.469t.47.2m.017-13.288q.29 0 .483-.2q.193-.202.193-.47q0-.29-.193-.492q-.193-.203-.488-.203q-.273 0-.469.203q-.196.202-.196.493q0 .267.2.468q.202.201.47.201");
}

</style>
