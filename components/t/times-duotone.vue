<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvbq5b4xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvbq5b4xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:times-duotone" /></template>
