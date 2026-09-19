<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfd-gok6c.css';
import '../../css/g/g369r0bza.css';
import '../../css/f/flo-2gl9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wfd-gok6c"/><path class="g369r0bza"/><path class="flo-2gl9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:running" /></template>
