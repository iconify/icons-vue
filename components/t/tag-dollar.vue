<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d62mt21tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d62mt21tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:tag-dollar" /></template>
