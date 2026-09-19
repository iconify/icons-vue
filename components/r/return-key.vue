<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de14d4b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="de14d4b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:return-key" /></template>
