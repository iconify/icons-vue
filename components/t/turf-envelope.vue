<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vunxkfbbd.css';
import '../../css/f/fsxxlibal.css';
import '../../css/o/okepkxbbb.css';
import '../../css/q/qtvldmb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="vunxkfbbd"/><circle class="fsxxlibal"/><circle class="okepkxbbb"/><path class="qtvldmb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-envelope" /></template>
