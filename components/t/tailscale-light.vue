<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8vvxucjh.css';
import '../../css/x/xvp3f-_7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c8vvxucjh"/><path class="xvp3f-_7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tailscale-light" /></template>
