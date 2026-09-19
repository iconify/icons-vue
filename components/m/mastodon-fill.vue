<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_4lxy4yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_4lxy4yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:mastodon-fill" /></template>
