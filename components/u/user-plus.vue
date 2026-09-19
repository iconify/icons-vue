<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rokj9f_9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rokj9f_9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:user-plus" /></template>
