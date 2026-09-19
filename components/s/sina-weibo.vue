<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r04k3wdfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r04k3wdfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:sina-weibo" /></template>
