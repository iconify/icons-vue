<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ismtb1bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ismtb1bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:triangle" /></template>
