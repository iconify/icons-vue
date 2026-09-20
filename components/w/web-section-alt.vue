<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6nuan2hq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6nuan2hq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:web-section-alt" /></template>
