<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb_frobnd.css';
import '../../css/l/l557xacfx.css';
import '../../css/q/qqhr9r1-v.css';
import '../../css/l/ljju7f6ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eb_frobnd"/><path class="l557xacfx"/><path class="qqhr9r1-v"/><path class="ljju7f6ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:package" /></template>
