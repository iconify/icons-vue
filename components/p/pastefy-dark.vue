<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx914upgl.css';
import '../../css/r/rc6--6b0h.css';
import '../../css/w/wmnw5bvdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dx914upgl"/><path class="rc6--6b0h"/><path class="wmnw5bvdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pastefy-dark" /></template>
