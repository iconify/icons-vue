<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6p030o4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c6p030o4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mastodon-logo-1-block" /></template>
