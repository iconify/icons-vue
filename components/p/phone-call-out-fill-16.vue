<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4m4ghapt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g4m4ghapt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-out-fill-16" /></template>
