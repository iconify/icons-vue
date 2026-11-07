<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_p9czbut.css';
import '../../css/x/xnfkpachl.css';
import '../../css/f/fvspzabcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_p9czbut"/><path class="xnfkpachl"/><path class="fvspzabcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-4-bold-duotone" /></template>
