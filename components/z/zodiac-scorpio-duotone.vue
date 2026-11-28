<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vto57bbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vto57bbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zodiac-scorpio-duotone" /></template>
