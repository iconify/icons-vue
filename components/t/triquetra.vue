<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-esylbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j-esylbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:triquetra" /></template>
