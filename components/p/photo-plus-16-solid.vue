<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7-ruyboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z7-ruyboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:photo-plus-16-solid" /></template>
