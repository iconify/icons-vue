<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y108lacqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="y108lacqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:white-heavy-check-mark-small" /></template>
