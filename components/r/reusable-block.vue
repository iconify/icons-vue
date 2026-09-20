<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enh3ep69x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="enh3ep69x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:reusable-block" /></template>
