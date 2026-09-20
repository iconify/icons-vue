<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oty3txbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oty3txbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:rainbow" /></template>
