<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr7sejb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr7sejb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:upstage" /></template>
