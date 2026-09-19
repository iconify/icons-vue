<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_m274e1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="e_m274e1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:pin" /></template>
