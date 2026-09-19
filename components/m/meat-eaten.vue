<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoo1qsb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zoo1qsb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:meat-eaten" /></template>
