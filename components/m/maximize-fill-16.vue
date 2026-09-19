<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdo805--h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jdo805--h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:maximize-fill-16" /></template>
