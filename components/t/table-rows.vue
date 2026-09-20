<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv1vpq53t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jv1vpq53t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:table-rows" /></template>
