<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc9txne7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kc9txne7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spine-arrow" /></template>
