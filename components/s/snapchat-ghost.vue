<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoou20b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoou20b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:snapchat-ghost" /></template>
