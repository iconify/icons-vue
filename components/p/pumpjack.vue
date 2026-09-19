<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-5sx6b5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="d-5sx6b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pumpjack" /></template>
