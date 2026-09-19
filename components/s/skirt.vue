<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jee5y5ssn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jee5y5ssn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:skirt" /></template>
