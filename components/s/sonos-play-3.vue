<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg7yu4bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg7yu4bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sonos-play-3" /></template>
