<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo903tb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yo903tb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:revolver" /></template>
