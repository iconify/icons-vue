<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gplo0fbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gplo0fbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:table-fill" /></template>
