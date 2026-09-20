<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9dno1bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9dno1bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:volume-mute" /></template>
