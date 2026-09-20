<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1x1g8b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1x1g8b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:milk-filled" /></template>
