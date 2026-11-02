<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my4upjy5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="my4upjy5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sleeping-in-shelter" /></template>
