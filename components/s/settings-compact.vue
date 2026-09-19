<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwlz_0bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lwlz_0bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:settings-compact" /></template>
