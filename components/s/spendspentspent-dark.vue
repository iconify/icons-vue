<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcrqbubeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dcrqbubeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spendspentspent-dark" /></template>
