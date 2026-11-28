<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aurab21qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aurab21qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:target-arrow-solid" /></template>
