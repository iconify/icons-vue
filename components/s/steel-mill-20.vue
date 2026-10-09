<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl_f1i0nt.css';
import '../../css/c/cr_3gebps.css';
import '../../css/z/z7zq9ab0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bl_f1i0nt"/><path class="cr_3gebps"/><path class="z7zq9ab0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:steel-mill-20" /></template>
