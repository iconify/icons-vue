<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exa614c9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="exa614c9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:minus" /></template>
