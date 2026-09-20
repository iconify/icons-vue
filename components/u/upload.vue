<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryc6sbc8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryc6sbc8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:upload" /></template>
