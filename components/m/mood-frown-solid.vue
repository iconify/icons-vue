<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/impn5pp0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="impn5pp0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mood-frown-solid" /></template>
