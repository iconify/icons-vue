<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg8vf0byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg8vf0byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:openapiinitiative" /></template>
