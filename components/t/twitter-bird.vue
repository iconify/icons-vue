<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhi9wsb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1003,"height":1000};
const content = `<path class="mhi9wsb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:twitter-bird" /></template>
