<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4nkcibgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q4nkcibgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:top-left-outline" /></template>
