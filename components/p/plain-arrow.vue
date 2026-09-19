<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgz_b5v2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qgz_b5v2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plain-arrow" /></template>
