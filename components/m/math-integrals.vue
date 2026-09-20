<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azhpgt8pr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azhpgt8pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-integrals" /></template>
