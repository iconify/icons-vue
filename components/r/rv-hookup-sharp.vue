<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8hh-utsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:rv-hookup-sharp" /></template>
<style>
.i8hh-utsb {
  fill: currentColor;
  d: path("m19.5 21.5l-1.4-1.4l1.1-1.1h-7.4q-.3.9-1.075 1.45T9 21t-1.712-.55T6.2 19H2v-9h6V7H2V5h15v12h2.15l-1.05-1.05l1.4-1.45L23 18zM10 10h5V7h-5zm-.288 8.713Q10 18.425 10 18t-.288-.712T9 17t-.712.288T8 18t.288.713T9 19t.713-.288");
}

</style>
