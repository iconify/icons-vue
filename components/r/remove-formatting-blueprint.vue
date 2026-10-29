<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/aygf7bbmo.css';
import '../../css/d/djt24lr8q.css';
import '../../css/b/bb31khzkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="aygf7bbmo wm-k"/><path class="djt24lr8q wm-k"/><path class="bb31khzkn wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:remove-formatting-blueprint" /></template>
