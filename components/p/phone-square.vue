<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mov5x5atu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="mov5x5atu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:phone-square" /></template>
