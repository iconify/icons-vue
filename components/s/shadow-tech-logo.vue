<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqo_owmxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqo_owmxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:shadow-tech-logo" /></template>
