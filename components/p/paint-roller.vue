<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/n/niw7-soza.css';
import '../../css/w/wu7w2tbza.css';
import '../../css/g/g8qulermz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="niw7-soza"/><path class="wu7w2tbza"/><path class="g8qulermz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:paint-roller" /></template>
