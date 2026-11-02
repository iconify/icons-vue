<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq8krpblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jq8krpblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:silent-fill" /></template>
