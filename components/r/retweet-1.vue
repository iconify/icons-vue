<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzw170b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":448};
const content = `<path class="kzw170b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:retweet-1" /></template>
