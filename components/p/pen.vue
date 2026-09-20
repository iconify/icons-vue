<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu70e7cqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu70e7cqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:pen" /></template>
