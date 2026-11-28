<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kruyp5nwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kruyp5nwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:waves-arrow-up" /></template>
