<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkc3rh37p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="wkc3rh37p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:photobucket" /></template>
