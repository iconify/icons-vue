<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uom6yvocs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uom6yvocs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:unlock-muted-line" /></template>
