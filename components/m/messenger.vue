<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvcno6uwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fvcno6uwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:messenger" /></template>
