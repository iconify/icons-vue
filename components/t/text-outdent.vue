<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyw-o0bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hyw-o0bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:text-outdent" /></template>
