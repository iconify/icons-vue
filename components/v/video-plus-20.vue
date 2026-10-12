<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wix0a5bey.css';
import '../../css/c/cdonwobot.css';
import '../../css/y/y4i3220kc.css';
import '../../css/z/zkdyo_ief.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wix0a5bey"/><path class="cdonwobot"/><path class="y4i3220kc"/><path class="zkdyo_ief"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:video-plus-20" /></template>
