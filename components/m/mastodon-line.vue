<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo6f8_brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo6f8_brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mastodon-line" /></template>
