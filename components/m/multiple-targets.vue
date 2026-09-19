<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tas0m7brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tas0m7brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:multiple-targets" /></template>
