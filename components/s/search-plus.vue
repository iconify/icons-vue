<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1yk5qbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1yk5qbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:search-plus" /></template>
