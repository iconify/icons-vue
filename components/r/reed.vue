<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7t7ksbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p7t7ksbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:reed" /></template>
