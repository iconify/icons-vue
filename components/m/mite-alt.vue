<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjuntkzkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qjuntkzkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mite-alt" /></template>
