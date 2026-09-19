<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb_xljp9g.css';
import '../../css/e/erkje89et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="hb_xljp9g"/><path class="erkje89et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sunbehindcloud" /></template>
