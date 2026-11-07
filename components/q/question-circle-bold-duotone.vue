<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpv5vhdla.css';
import '../../css/z/z-85vlbmo.css';
import '../../css/x/x41xvfi0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpv5vhdla"/><path class="z-85vlbmo"/><path class="x41xvfi0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:question-circle-bold-duotone" /></template>
