<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu3j9k8yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu3j9k8yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tablets" /></template>
