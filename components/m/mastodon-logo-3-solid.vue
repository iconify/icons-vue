<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb5d0xh1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lb5d0xh1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mastodon-logo-3-solid" /></template>
