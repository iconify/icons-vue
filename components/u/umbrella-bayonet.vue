<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7pus7n3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l7pus7n3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:umbrella-bayonet" /></template>
