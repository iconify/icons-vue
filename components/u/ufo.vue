<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyjeihbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":448};
const content = `<path class="kyjeihbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:ufo" /></template>
