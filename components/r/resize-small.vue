<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpnf4vmir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="zpnf4vmir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:resize-small" /></template>
