<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okz8j0hfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okz8j0hfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-split-vertical-filled" /></template>
