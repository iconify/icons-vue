<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnb8f3bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jnb8f3bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wealthfolio-light" /></template>
