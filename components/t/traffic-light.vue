<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuxol8bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zuxol8bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:traffic-light" /></template>
