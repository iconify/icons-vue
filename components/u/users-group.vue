<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by8miib6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by8miib6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:users-group" /></template>
