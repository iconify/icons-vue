<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeorc5t3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeorc5t3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sword" /></template>
