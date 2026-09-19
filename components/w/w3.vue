<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1efuxbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="n1efuxbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:w3" /></template>
