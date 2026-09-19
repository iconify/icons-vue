<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmvzjachi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gmvzjachi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:trapezoid-up-line-vertical" /></template>
