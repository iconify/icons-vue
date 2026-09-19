<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aob6fmi_e.css';
import '../../css/n/n71_44j2k.css';
import '../../css/w/w9orhbbyr.css';
import '../../css/q/qiefsmlyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aob6fmi_e"/><path class="n71_44j2k"/><path class="w9orhbbyr"/><path class="qiefsmlyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:revolvinghearts" /></template>
