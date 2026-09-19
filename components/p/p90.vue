<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amie3nbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="amie3nbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:p90" /></template>
