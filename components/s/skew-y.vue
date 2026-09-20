<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugsr7ob4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugsr7ob4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:skew-y" /></template>
