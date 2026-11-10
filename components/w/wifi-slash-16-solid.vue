<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjsjm40yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zjsjm40yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:wifi-slash-16-solid" /></template>
