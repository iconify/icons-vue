<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe8a6zxhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xe8a6zxhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:minus-small-outline" /></template>
