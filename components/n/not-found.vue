<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leya4mt_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leya4mt_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:not-found" /></template>
