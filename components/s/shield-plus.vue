<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr35wbcpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr35wbcpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shield-plus" /></template>
