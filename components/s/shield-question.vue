<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axvz_9b4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axvz_9b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:shield-question" /></template>
