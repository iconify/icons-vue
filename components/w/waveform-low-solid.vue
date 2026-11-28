<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6ydnjdqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6ydnjdqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:waveform-low-solid" /></template>
