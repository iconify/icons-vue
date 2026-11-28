<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owynusbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owynusbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:qr-code-check" /></template>
