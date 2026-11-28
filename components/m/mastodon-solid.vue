<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei03hwbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei03hwbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mastodon-solid" /></template>
