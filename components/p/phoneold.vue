<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2f-5pork.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="h2f-5pork"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:phoneold" /></template>
