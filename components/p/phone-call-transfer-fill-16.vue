<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4e87f__o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z4e87f__o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-transfer-fill-16" /></template>
