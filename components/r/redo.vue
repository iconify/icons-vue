<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnzfu0s5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnzfu0s5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:redo" /></template>
