<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6ychc3fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6ychc3fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:move-outline" /></template>
