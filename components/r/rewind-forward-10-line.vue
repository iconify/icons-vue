<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1vun7bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1vun7bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-10-line" /></template>
