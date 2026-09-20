<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6zbidbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p6zbidbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tag-with-peso" /></template>
