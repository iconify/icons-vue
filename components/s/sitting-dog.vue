<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_smd11zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n_smd11zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sitting-dog" /></template>
