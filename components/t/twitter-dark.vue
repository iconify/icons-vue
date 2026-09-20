<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyazfqf8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lyazfqf8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:twitter-dark" /></template>
