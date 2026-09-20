<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs1kckuxk.css';
import '../../css/y/ytnuvpdkn.css';
import '../../css/p/p4itqc0gf.css';
import '../../css/y/yav708big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xs1kckuxk"/><path class="ytnuvpdkn"/><path class="p4itqc0gf"/><path class="yav708big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-onenote-dark" /></template>
