<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj8r7vbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fj8r7vbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-wearing-waiters-attire-holding-tray-with-wine-glass" /></template>
