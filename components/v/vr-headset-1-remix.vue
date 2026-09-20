<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yawj8c32a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yawj8c32a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:vr-headset-1-remix" /></template>
