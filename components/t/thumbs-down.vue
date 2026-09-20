<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywyq4xb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ywyq4xb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:thumbs-down" /></template>
