<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ettwtho0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ettwtho0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:swiss-army-knife" /></template>
