<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/gjtghudtp.css';
import '../../css/n/nip8kwy2i.css';
import '../../css/t/tri54cc7d.css';
import '../../css/v/vxbqahbvv.css';
import '../../css/w/w1u5mzbwz.css';
import '../../css/l/ltvexmk4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="gjtghudtp wm-deco"/><path class="nip8kwy2i wm-deco"/><path class="tri54cc7d wm-k"/><path class="vxbqahbvv wm-a"/><path class="w1u5mzbwz wm-a"/><path class="ltvexmk4n wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mouse-blueprint" /></template>
