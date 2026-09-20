<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgz-9gbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgz-9gbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:window-restore" /></template>
