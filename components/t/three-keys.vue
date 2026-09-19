<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygum6sb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ygum6sb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:three-keys" /></template>
