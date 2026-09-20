<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvcj7_bet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvcj7_bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:music-note" /></template>
