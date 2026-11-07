<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpv5vhdla.css';
import '../../css/c/c36_0z9jv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpv5vhdla"/><path class="c36_0z9jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stop-circle-bold-duotone" /></template>
