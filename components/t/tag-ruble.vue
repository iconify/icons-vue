<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtqh2o4ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gtqh2o4ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:tag-ruble" /></template>
