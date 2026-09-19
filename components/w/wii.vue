<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guba09b7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="guba09b7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:wii" /></template>
