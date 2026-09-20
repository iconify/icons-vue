<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6ngwtb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d6ngwtb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:prostate" /></template>
