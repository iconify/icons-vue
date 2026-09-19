<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2mwuibgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e2mwuibgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:weight-hanging" /></template>
