<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvor7v2hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvor7v2hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tick-circle-filled" /></template>
