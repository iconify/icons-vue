<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyzxg9-uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="iyzxg9-uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:monitor-slash-light" /></template>
