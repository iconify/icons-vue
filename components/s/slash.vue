<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awuyar9iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awuyar9iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:slash" /></template>
