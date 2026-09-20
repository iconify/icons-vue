<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svq151qyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svq151qyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mastodon-line" /></template>
