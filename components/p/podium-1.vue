<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgg_olbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgg_olbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:podium-1" /></template>
