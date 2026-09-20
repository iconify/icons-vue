<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iczn8db2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iczn8db2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mastodon-logo-2-solid" /></template>
