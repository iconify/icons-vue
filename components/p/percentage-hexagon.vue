<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpj-7ybes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpj-7ybes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:percentage-hexagon" /></template>
