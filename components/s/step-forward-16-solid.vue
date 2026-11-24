<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7tndbczd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q7tndbczd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:step-forward-16-solid" /></template>
