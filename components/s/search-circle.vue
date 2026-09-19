<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om11f2y7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om11f2y7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:search-circle" /></template>
