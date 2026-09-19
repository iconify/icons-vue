<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5_t2bzyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="a5_t2bzyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:road" /></template>
