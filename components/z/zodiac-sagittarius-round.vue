<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7xh-mb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7xh-mb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-sagittarius-round" /></template>
