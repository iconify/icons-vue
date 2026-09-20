<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj36z8w0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj36z8w0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:remote-wave" /></template>
