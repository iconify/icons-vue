<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc6ozldmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gc6ozldmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:share-link-solid" /></template>
