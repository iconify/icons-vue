<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb_cwr8ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb_cwr8ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:playlist-play" /></template>
