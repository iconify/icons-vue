<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlz7jq-ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zlz7jq-ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wood-club" /></template>
