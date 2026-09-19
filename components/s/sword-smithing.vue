<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs0f7u05m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qs0f7u05m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sword-smithing" /></template>
