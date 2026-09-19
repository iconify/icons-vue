<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0kie0bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="j0kie0bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:untappd" /></template>
