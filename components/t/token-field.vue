<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz05-gtnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bz05-gtnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-field" /></template>
