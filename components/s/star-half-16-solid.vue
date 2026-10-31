<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4_8j7lyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n4_8j7lyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:star-half-16-solid" /></template>
