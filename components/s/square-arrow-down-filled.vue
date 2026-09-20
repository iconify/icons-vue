<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clrr77bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clrr77bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-arrow-down-filled" /></template>
