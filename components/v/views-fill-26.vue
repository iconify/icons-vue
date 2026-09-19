<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4sdkkska.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="f4sdkkska"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:views-fill-26" /></template>
