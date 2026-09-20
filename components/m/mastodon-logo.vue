<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8n-h5bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="z8n-h5bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:mastodon-logo" /></template>
