<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fui64t4ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fui64t4ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:message" /></template>
