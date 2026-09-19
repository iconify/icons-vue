<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okysa4a1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="okysa4a1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:star-struck" /></template>
