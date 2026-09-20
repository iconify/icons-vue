<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_1x8qb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_1x8qb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tag-solid" /></template>
