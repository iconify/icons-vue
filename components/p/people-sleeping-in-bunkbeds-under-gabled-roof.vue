<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab7d9sbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ab7d9sbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:people-sleeping-in-bunkbeds-under-gabled-roof" /></template>
