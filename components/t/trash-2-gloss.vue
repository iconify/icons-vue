<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvsw-vb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvsw-vb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:trash-2-gloss" /></template>
