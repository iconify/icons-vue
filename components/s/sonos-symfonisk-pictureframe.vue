<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a60w55xio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a60w55xio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sonos-symfonisk-pictureframe" /></template>
