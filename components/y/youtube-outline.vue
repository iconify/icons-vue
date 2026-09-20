<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av_sbbbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="av_sbbbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:youtube-outline" /></template>
