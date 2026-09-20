<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvdhh0tlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="vvdhh0tlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:table-tennis-11" /></template>
