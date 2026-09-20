<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu9hx0bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gu9hx0bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:salesforce-dark" /></template>
