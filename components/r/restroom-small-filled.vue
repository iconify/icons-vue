<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxyxf87ci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vxyxf87ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:restroom-small-filled" /></template>
