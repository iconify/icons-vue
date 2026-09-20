<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8vxjegac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8vxjegac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:shutter-filled" /></template>
