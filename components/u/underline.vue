<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3yy1_2al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p3yy1_2al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:underline" /></template>
