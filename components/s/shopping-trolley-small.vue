<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw2d8kh4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qw2d8kh4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:shopping-trolley-small" /></template>
