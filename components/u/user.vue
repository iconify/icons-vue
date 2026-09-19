<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7enk3mab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":328,"height":512};
const content = `<path class="e7enk3mab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:user" /></template>
