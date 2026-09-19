<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj8y-ybio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj8y-ybio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:mastodon-filled" /></template>
