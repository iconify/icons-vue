<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac-mt5boh.css';
import '../../css/v/vxr1g-bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ac-mt5boh"/><path class="vxr1g-bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:verdaccio-light" /></template>
