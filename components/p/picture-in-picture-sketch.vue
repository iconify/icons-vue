<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/flbl44beh.css';
import '../../css/y/yp_dyqbmy.css';
import '../../css/i/igksilbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="flbl44beh"/><path class="wm-k yp_dyqbmy"/><path class="igksilbgd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:picture-in-picture-sketch" /></template>
