<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7d6a-bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7d6a-bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:social-twitter-circular" /></template>
