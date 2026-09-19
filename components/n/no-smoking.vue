<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr31r9bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr31r9bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-smoking" /></template>
