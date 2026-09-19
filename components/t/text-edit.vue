<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmw7fe3td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pmw7fe3td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:text-edit" /></template>
