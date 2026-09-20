<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/funp-8bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="funp-8bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sign-beside-person-walking" /></template>
