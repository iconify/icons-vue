<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elg8rhbmi.css';
import '../../css/r/rk-ri1bqz.css';
import '../../css/b/bivwwb2cw.css';
import '../../css/c/cpztshyvx.css';
import '../../css/r/rxv6fxb8e.css';
import '../../css/s/s8zl27fca.css';
import '../../css/b/bn3v3rkcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="elg8rhbmi"/><path class="rk-ri1bqz"/><path class="bivwwb2cw"/><path class="cpztshyvx"/><path class="rxv6fxb8e"/><path class="s8zl27fca"/><path class="bn3v3rkcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pigeonpod-light" /></template>
