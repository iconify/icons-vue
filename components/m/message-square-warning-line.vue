<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6cb_bcgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6cb_bcgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-warning-line" /></template>
