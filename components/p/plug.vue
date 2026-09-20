<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6xjo617a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6xjo617a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:plug" /></template>
