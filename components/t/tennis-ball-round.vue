<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-5j89ong.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-5j89ong"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tennis-ball-round" /></template>
