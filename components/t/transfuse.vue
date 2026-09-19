<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9ear3k3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h9ear3k3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:transfuse" /></template>
