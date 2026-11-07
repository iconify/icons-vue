<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxiuf1b8p.css';
import '../../css/j/jq9qq8bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxiuf1b8p"/><path class="jq9qq8bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scaling-bold" /></template>
