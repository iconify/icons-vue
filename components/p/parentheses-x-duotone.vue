<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz8yk_b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz8yk_b3a primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:parentheses-x-duotone" /></template>
