<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9ulzb9qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v9ulzb9qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:toucan-crossing" /></template>
