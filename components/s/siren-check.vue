<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7z3uvz1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:siren-check" /></template>
<style>
.a7z3uvz1f {
  fill: currentColor;
  d: path("M14.347 20.71q-1.25-1.25-1.25-3.056t1.25-3.057t3.057-1.25t3.057 1.25q1.25 1.251 1.25 3.057t-1.25 3.056t-3.057 1.251t-3.057-1.25m2.351-1.172l3.148-3.143l-.627-.627l-2.521 2.51l-1.11-1.11l-.626.633zM4.616 20q-.672 0-1.144-.472T3 18.385v-1.52q0-.67.472-1.143q.472-.472 1.144-.472h1.211v-5.115q0-2.56 1.797-4.347T12 4t4.376 1.788q1.797 1.787 1.797 4.347v.863l-.382-.024q-.189-.012-.387-.012q-2.804 0-4.758 1.96t-1.954 4.732q0 .602.105 1.191t.32 1.155zm4.057-7.058h1v-2.807q0-.96.684-1.634T12 7.827v-1q-1.38 0-2.354.964q-.973.963-.973 2.343z");
}

</style>
