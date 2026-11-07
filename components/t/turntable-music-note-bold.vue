<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgzavdeog.css';
import '../../css/h/h5nyfzb8a.css';
import '../../css/i/i9po9cwhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bgzavdeog"/><path class="h5nyfzb8a"/><path clip-rule="evenodd" class="i9po9cwhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:turntable-music-note-bold" /></template>
