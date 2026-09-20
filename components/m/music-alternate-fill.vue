<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9_9czbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9_9czbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:music-alternate-fill" /></template>
