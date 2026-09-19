<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7pcg00kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u7pcg00kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:snowflake" /></template>
