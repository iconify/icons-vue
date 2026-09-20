<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv4lvww3m.css';
import '../../css/p/pug9g9bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="iv4lvww3m"/><path class="pug9g9bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rhasspy" /></template>
