<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqrmmeb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqrmmeb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:wear-headset" /></template>
