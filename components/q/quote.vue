<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2pm3-mel.css';
import '../../css/i/id9ydeb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2pm3-mel"/><path class="id9ydeb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:quote" /></template>
