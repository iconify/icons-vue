<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plr8h7rnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="plr8h7rnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:remix-wordmark" /></template>
