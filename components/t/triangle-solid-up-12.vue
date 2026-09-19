<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia0t11r-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ia0t11r-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:triangle-solid-up-12" /></template>
