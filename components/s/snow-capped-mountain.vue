<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo26x2-5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wo26x2-5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:snow-capped-mountain" /></template>
