<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el96rjbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="el96rjbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorcycle-and-euro" /></template>
