<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbik9_v8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbik9_v8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:spicebottle" /></template>
