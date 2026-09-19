<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as7rq8bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="as7rq8bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:play-back-circle-sharp" /></template>
