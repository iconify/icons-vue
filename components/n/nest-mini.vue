<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s68r3c0xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s68r3c0xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nest-mini" /></template>
