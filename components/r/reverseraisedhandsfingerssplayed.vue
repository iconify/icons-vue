<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fex8l3b8p.css';
import '../../css/r/rw715wbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fex8l3b8p"/><path class="rw715wbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:reverseraisedhandsfingerssplayed" /></template>
