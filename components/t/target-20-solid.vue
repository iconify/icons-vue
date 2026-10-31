<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgk-jqj6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wgk-jqj6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:target-20-solid" /></template>
