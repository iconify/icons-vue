<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te4iupkoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shades-closed-outline-sharp" /></template>
<style>
.te4iupkoj {
  fill: currentColor;
  d: path("M3.98 21.02V4H3V3h18v1h-.98v17.02h-1.068q-.344-.991-1.216-1.611q-.87-.62-1.967-.62q-1.102 0-1.941.62q-.84.62-1.184 1.61h-1.313q-.339-.99-1.171-1.61t-1.93-.62q-1.12 0-1.992.62q-.87.62-1.215 1.61zm1-1.77q.503-.575 1.208-.951t1.524-.462V4H4.98zm3.732-1.413q.863.086 1.584.513t1.204 1.104V4H8.711zM12.5 19.41q.483-.658 1.194-1.072t1.575-.501V4H12.5zm6.52-.116V4h-2.75v13.837q.824.086 1.536.472q.711.385 1.213.985M7.712 4H4.98zM11.5 4H8.711zm3.77 0H12.5zm3.75 0h-2.75zM12.5 4h-1z");
}

</style>
