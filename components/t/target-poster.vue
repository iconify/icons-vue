<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/befr52blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="befr52blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:target-poster" /></template>
