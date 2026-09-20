<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adhxuu-rl.css';
import '../../css/l/l520-dkdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adhxuu-rl"/><path class="l520-dkdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:pinejs" /></template>
