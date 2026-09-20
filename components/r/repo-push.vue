<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkv1f1b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="tkv1f1b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-push" /></template>
