<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvxpmlmwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvxpmlmwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-rounded-check" /></template>
