<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caq0d6f2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caq0d6f2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:square-small" /></template>
