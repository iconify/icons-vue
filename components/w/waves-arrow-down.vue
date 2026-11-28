<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmucpsbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmucpsbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:waves-arrow-down" /></template>
