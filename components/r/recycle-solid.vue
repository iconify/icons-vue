<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5yt5hneb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5yt5hneb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:recycle-solid" /></template>
