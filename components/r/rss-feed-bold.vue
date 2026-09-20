<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsq76_m7h.css';
import '../../css/g/ge4x6hrjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsq76_m7h"/><path class="ge4x6hrjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:rss-feed-bold" /></template>
