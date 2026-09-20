<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snl_hb.css';
import '../../css/x/x93a4q.css';
import '../../css/b/botfzx.css';
import '../../css/c/cx-from-7px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVG262Nbd6S"><path class="snl_hb"/><circle class="x93a4q"/></mask></defs><path mask="url(#SVG262Nbd6S)" class="botfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:switch-off-filled-to-switch-filled-transition" /></template>
