<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnr7p1g2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnr7p1g2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:search" /></template>
