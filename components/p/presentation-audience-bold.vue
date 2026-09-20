<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzuqjj_tm.css';
import '../../css/j/jn7afdxga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzuqjj_tm"/><path class="jn7afdxga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:presentation-audience-bold" /></template>
