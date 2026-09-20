<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2pg_dqyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="c2pg_dqyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:paragraph-center" /></template>
