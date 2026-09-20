<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udoc8zboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udoc8zboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:webpack" /></template>
