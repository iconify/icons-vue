<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwp2pllyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwp2pllyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:speaker-3-fill" /></template>
