<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/o/om1jfjbon.css';
import '../../css/h/hghunxbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(3 6)" class="jtowsomii"><path class="om1jfjbon"/><circle class="hghunxbuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:wifi" /></template>
