<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u98105u5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u98105u5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-crouching-wearing-backpack-and-headlamp" /></template>
