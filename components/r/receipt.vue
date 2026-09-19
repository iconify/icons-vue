<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tosj05bbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tosj05bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:receipt" /></template>
