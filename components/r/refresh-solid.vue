<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkd2uny5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wkd2uny5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:refresh-solid" /></template>
