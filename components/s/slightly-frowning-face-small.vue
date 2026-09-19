<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x57nb3bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="x57nb3bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:slightly-frowning-face-small" /></template>
