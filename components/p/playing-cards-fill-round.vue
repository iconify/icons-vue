<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq89u5v2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq89u5v2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playing-cards-fill-round" /></template>
