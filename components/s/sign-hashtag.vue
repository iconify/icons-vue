<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbss98bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbss98bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:sign-hashtag" /></template>
