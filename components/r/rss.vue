<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn6jciybe.css';
import '../../css/n/nxbv23bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vn6jciybe"/><path class="nxbv23bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rss" /></template>
