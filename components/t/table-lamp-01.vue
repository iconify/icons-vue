<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxhvmirsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxhvmirsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:table-lamp-01" /></template>
