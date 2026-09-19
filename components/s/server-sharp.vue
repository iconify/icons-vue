<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7b52bcxl.css';
import '../../css/z/zvlz7ab9o.css';
import '../../css/r/roko4zy8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c7b52bcxl"/><path class="zvlz7ab9o"/><path class="roko4zy8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:server-sharp" /></template>
