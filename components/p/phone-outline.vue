<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhuug4b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bhuug4b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:phone-outline" /></template>
