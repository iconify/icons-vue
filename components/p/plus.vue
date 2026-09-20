<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9rxmmbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f9rxmmbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:plus" /></template>
