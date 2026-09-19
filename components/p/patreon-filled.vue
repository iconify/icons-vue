<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay40b4-uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay40b4-uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:patreon-filled" /></template>
