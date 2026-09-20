<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpxvi_bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpxvi_bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:outbox-filled" /></template>
