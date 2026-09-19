<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqo2eehvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hqo2eehvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sniffing-dog" /></template>
