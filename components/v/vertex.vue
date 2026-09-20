<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyv23pb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qyv23pb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:vertex" /></template>
