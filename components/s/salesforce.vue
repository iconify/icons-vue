<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojx1uh95k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ojx1uh95k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:salesforce" /></template>
