<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr9y3zfcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr9y3zfcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:share-2-gloss" /></template>
