<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjspt_blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vjspt_blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:retweet" /></template>
