<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgbx3xbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgbx3xbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:niconico" /></template>
