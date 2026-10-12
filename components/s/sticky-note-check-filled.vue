<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxvb6cctw.css';
import '../../css/n/n5sg21b7n.css';
import '../../css/z/zj890cb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxvb6cctw"/><path class="n5sg21b7n"/><path class="zj890cb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sticky-note-check-filled" /></template>
