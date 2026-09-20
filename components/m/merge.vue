<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7599ebdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7599ebdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:merge" /></template>
