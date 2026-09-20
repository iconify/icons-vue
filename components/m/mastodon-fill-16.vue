<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpds53b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kpds53b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:mastodon-fill-16" /></template>
