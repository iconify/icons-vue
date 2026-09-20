<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft9lsfbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft9lsfbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:volume-off" /></template>
