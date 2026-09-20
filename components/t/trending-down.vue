<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfaqad7fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfaqad7fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:trending-down" /></template>
