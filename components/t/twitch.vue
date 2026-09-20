<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1fojfknm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1fojfknm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:twitch" /></template>
