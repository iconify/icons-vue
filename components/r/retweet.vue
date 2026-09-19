<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2bw7kbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1360,"height":1000};
const content = `<path class="l2bw7kbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:retweet" /></template>
