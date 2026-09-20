<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm-l3gteu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm-l3gteu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:wine-off" /></template>
