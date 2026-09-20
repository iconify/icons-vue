<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_itiabuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_itiabuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:retweet-logo-block" /></template>
