<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mozc1bb5c.css';
import '../../css/a/a1ypjyb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mozc1bb5c"/><path class="a1ypjyb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:phonewithpage" /></template>
