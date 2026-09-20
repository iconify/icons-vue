<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im577vr3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im577vr3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:zelda" /></template>
