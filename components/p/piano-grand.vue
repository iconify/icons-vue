<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjn5kuzfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjn5kuzfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:piano-grand" /></template>
