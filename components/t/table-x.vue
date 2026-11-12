<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni8k4pbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni8k4pbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:table-x" /></template>
