<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob3c1xbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob3c1xbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sonos-five" /></template>
