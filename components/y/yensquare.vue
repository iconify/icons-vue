<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svxlfjbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="svxlfjbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:yensquare" /></template>
