<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz1or2rab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz1or2rab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:turn-left-up" /></template>
