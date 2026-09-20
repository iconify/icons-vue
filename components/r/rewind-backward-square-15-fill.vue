<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jblxonclo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jblxonclo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-backward-square-15-fill" /></template>
