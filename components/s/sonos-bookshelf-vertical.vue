<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i778ovvzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i778ovvzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sonos-bookshelf-vertical" /></template>
