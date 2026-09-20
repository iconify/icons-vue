<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2je7_6ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2je7_6ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:pocket-logo-bold" /></template>
