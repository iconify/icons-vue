<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcmzzw6so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fcmzzw6so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:snout" /></template>
