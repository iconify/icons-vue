<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sia-jfb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sia-jfb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:scissors" /></template>
