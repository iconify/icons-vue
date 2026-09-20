<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fws7slz-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fws7slz-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:projector-screen-off-outline" /></template>
