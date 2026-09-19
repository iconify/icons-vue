<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sokxb_p0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sokxb_p0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:volume-up-alt" /></template>
