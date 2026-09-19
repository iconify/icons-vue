<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npuhqsm5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="npuhqsm5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:photo-16-solid" /></template>
