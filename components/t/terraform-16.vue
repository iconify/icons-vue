<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ory-dgksp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ory-dgksp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:terraform-16" /></template>
