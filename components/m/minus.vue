<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fossa55ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="fossa55ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:minus" /></template>
