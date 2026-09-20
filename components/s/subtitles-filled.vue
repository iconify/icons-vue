<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2p3jbbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l2p3jbbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:subtitles-filled" /></template>
