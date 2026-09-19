<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h616hccya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h616hccya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:water-sharp" /></template>
