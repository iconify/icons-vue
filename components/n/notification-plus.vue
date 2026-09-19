<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg2tb8bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg2tb8bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:notification-plus" /></template>
