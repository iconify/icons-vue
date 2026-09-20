<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v620r637v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v620r637v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sun-remix" /></template>
