<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqf4hs3wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqf4hs3wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:puzzle" /></template>
