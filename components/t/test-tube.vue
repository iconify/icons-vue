<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjzfalb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjzfalb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:test-tube" /></template>
