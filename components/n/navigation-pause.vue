<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhogt5lio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhogt5lio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-pause" /></template>
