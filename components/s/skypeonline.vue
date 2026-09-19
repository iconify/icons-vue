<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh-t99bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="nh-t99bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:skypeonline" /></template>
