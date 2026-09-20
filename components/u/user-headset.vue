<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkgnmvqjs.css';
import '../../css/q/qxlpaybyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkgnmvqjs"/><path class="qxlpaybyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:user-headset" /></template>
