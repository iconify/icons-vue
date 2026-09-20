<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc95oj5yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc95oj5yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sov" /></template>
