<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lup9ydbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lup9ydbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:type-outline" /></template>
