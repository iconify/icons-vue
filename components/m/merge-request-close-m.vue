<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybfzkdb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ybfzkdb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:merge-request-close-m" /></template>
