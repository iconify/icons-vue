<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n14ga01-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n14ga01-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:manual-meat-grinder" /></template>
