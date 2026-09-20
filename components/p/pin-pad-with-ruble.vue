<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v76j5s1uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v76j5s1uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pin-pad-with-ruble" /></template>
