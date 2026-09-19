<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7y4-ubod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7y4-ubod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:monitor-fill" /></template>
