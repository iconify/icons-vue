<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzh2_5mwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzh2_5mwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sparkle-duotone" /></template>
