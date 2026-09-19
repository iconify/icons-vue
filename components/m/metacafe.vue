<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8z7ab9xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":488};
const content = `<path class="v8z7ab9xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:metacafe" /></template>
