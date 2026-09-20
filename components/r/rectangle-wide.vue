<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liotcnavo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="liotcnavo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:rectangle-wide" /></template>
