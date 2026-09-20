<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqmpk3elo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqmpk3elo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:star-fill-24" /></template>
