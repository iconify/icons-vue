<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inkqubb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inkqubb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:panel-top-bottom-dashed" /></template>
