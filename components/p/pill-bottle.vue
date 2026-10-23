<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe43_rbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe43_rbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pill-bottle" /></template>
