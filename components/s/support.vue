<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlt2-rbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlt2-rbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:support" /></template>
