<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bva6ccbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bva6ccbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:step-out" /></template>
