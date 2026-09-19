<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qafyagj9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qafyagj9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:view-grid-small" /></template>
