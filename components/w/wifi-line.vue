<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geya-bbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geya-bbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wifi-line" /></template>
