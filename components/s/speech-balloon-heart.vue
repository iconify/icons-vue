<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbtcz_bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kbtcz_bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:speech-balloon-heart" /></template>
