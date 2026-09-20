<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhujb7w9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhujb7w9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:waving-hand" /></template>
