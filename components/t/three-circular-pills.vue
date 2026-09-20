<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_pxrxg6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g_pxrxg6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-circular-pills" /></template>
