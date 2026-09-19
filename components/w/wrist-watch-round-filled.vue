<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8ikm3bfk.css';
import '../../css/p/p39-tabus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8ikm3bfk"/><path class="p39-tabus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wrist-watch-round-filled" /></template>
