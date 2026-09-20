<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkanf8r8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkanf8r8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-25-small" /></template>
