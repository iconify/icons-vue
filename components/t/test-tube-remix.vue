<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez_cv9rsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ez_cv9rsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:test-tube-remix" /></template>
