<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im26rieus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="im26rieus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tank-fill" /></template>
