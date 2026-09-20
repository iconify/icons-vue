<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xza0rac-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xza0rac-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:qr-code-outline" /></template>
