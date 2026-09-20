<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/curl4d8tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="curl4d8tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vimeo-livestream" /></template>
