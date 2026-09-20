<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlzfj5w3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zlzfj5w3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:medium-outline" /></template>
