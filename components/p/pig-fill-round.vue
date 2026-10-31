<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt_2g92wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt_2g92wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pig-fill-round" /></template>
