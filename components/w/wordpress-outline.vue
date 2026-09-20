<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8svl7bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r8svl7bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:wordpress-outline" /></template>
