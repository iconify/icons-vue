<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6tcecw7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o6tcecw7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:plaque" /></template>
