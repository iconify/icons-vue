<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8vvxucjh.css';
import '../../css/l/l52-p_urh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c8vvxucjh"/><path class="l52-p_urh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tailscale-light" /></template>
