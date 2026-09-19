<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijr-y-b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="ijr-y-b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:stiletto" /></template>
