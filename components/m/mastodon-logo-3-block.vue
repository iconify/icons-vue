<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6gw00hkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z6gw00hkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mastodon-logo-3-block" /></template>
