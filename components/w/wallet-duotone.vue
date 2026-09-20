<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf6-upbrn.css';
import '../../css/q/qs8co3srk.css';
import '../../css/q/qs4x5kbiy.css';
import '../../css/i/i2xzaiewc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf6-upbrn"/><path class="qs8co3srk"/><path class="qs4x5kbiy"/><rect class="i2xzaiewc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:wallet-duotone" /></template>
