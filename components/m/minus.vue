<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om3rctyno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="om3rctyno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:minus" /></template>
