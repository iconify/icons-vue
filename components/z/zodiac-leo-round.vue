<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vknv35b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vknv35b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-leo-round" /></template>
