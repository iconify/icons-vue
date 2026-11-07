<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8i3b9xno.css';
import '../../css/x/xbxy7ib5r.css';
import '../../css/c/c0tgf1saz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8i3b9xno"/><path class="xbxy7ib5r"/><path class="c0tgf1saz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-2-bold-duotone" /></template>
