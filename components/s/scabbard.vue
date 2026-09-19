<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrj_akb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jrj_akb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:scabbard" /></template>
