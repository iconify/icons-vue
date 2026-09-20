<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il_ly38gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="il_ly38gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:send" /></template>
