<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s90m0hzje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="s90m0hzje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:servicenow" /></template>
