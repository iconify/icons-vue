<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd5vm9b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fd5vm9b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:plus1" /></template>
