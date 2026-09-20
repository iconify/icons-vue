<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f09isdbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:recent-actors-outline-sharp" /></template>
<style>
.f09isdbhi {
  fill: currentColor;
  d: path("M1.77 18V6h12v12zm1-2.573q1.1-.708 2.35-1.106t2.65-.398t2.65.398t2.35 1.106V7h-10zm5-.504q-1.16 0-2.328.356t-2.234 1.087V17h9.219v-.635q-1.048-.673-2.244-1.057q-1.196-.385-2.414-.385m-1.726-2.697q-.716-.717-.716-1.726t.716-1.726q.717-.716 1.726-.716q1.01 0 1.726.716q.717.716.717 1.726t-.717 1.726t-1.726.716t-1.726-.716m1.726-.249q.616 0 1.047-.43q.43-.432.43-1.047t-.43-1.046t-1.047-.431t-1.046.43t-.43 1.047t.43 1.046t1.046.431M17 18V6h1v12zm4.23 0V6h1v12zM7.828 17");
}

</style>
