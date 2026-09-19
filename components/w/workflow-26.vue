<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf6lfvb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="rf6lfvb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:workflow-26" /></template>
