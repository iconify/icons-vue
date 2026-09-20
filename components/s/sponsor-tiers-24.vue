<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcrc-8b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcrc-8b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sponsor-tiers-24" /></template>
