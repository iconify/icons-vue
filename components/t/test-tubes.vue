<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tigx9-xcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tigx9-xcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:test-tubes" /></template>
