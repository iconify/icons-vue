<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac6pctzqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ac6pctzqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:minus" /></template>
