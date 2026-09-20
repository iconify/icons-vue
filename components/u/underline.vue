<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk85vbjug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hk85vbjug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:underline" /></template>
