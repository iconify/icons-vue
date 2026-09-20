<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwu1xfb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kwu1xfb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:split-h" /></template>
