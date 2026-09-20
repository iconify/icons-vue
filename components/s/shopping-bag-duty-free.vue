<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq95s7sjx.css';
import '../../css/g/gpq-8xbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq95s7sjx"/><path class="gpq-8xbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:shopping-bag-duty-free" /></template>
