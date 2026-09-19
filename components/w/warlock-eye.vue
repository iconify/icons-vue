<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5ktkqq5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d5ktkqq5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:warlock-eye" /></template>
