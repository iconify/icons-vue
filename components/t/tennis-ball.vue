<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_481206c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o_481206c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tennis-ball" /></template>
