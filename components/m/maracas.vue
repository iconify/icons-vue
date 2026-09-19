<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byqln5o1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="byqln5o1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:maracas" /></template>
