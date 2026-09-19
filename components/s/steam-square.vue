<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bicq4ibjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="bicq4ibjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:steam-square" /></template>
