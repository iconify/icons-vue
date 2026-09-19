<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3w_0bctb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v3w_0bctb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:triangle-right-12" /></template>
