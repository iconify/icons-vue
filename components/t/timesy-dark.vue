<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq5b8bbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wq5b8bbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:timesy-dark" /></template>
