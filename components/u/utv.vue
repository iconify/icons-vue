<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t34__wbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t34__wbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utv" /></template>
