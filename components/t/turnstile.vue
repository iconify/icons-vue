<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzmpkfi4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uzmpkfi4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:turnstile" /></template>
