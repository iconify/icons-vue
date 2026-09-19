<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_ofxbc0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="y_ofxbc0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:staff-snake" /></template>
