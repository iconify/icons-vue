<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i77zc0m-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i77zc0m-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:quote" /></template>
