<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr1rmbctj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lr1rmbctj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:sparkles-fill" /></template>
