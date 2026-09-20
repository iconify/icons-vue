<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8up-1bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j8up-1bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rounded-triangle-up-outline" /></template>
