<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6-tw7fdl.css';
import '../../css/u/u57zsmbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6-tw7fdl"/><path class="u57zsmbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ticket-outline" /></template>
