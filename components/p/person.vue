<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4yu6jjnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g4yu6jjnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:person" /></template>
