<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg4uccb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cg4uccb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:turnstile" /></template>
