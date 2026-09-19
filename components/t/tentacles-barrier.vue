<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glxx8vb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="glxx8vb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tentacles-barrier" /></template>
