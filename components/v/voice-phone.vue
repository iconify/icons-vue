<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqfv87bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqfv87bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:voice-phone" /></template>
