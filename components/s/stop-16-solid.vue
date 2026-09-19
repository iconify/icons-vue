<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol9rll3qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<rect class="ol9rll3qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:stop-16-solid" /></template>
