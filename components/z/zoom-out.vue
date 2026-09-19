<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3r41qfxn.css';
import '../../css/s/str-f1rew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="t3r41qfxn"/><path class="str-f1rew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:zoom-out" /></template>
