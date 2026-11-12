<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd2317bpb.css';
import '../../css/d/dd62ynr7u.css';
import '../../css/q/qd-usjb9k.css';
import '../../css/e/efa-oubof.css';
import '../../css/c/cxjwkwbqh.css';
import '../../css/b/bh4vtcb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rd2317bpb"/><path class="dd62ynr7u"/><path class="qd-usjb9k"/><path class="efa-oubof"/><path class="cxjwkwbqh"/><path class="bh4vtcb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:solarassistant-light" /></template>
