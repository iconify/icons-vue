<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjwe_m-4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cjwe_m-4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sinagot" /></template>
