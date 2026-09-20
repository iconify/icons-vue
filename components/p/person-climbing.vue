<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to8q6wbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="to8q6wbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-climbing" /></template>
