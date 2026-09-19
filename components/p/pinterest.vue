<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmswvl73a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="hmswvl73a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:pinterest" /></template>
