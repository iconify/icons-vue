<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdrk782lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdrk782lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:message-square" /></template>
