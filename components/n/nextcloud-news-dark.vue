<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ood9f2bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ood9f2bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-news-dark" /></template>
