<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1en0g5bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1en0g5bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-square-30-fill" /></template>
