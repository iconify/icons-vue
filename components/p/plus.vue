<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9ekx63oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9ekx63oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:plus" /></template>
