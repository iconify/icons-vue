<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcop5xikc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="vcop5xikc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:y-combinator" /></template>
