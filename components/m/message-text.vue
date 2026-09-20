<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elsly3bbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="elsly3bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:message-text" /></template>
