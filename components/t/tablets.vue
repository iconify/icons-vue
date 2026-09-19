<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eugt4cqou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eugt4cqou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:tablets" /></template>
