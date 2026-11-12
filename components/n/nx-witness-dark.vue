<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kegoc-59e.css';
import '../../css/y/yn5w2kbbj.css';
import '../../css/u/uc21-y-ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kegoc-59e"/><path class="yn5w2kbbj"/><path class="uc21-y-ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nx-witness-dark" /></template>
