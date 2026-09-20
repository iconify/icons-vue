<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwm0kfbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwm0kfbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rewe" /></template>
