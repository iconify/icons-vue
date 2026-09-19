<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs5wzbb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs5wzbb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:xls-01" /></template>
