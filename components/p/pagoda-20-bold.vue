<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygoozhsqh.css';
import '../../css/j/jjv4m6b-s.css';
import '../../css/f/fylhtkbms.css';
import '../../css/g/gpgqfdbap.css';
import '../../css/a/a79tt-b_j.css';
import '../../css/e/ep9tu-o-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ygoozhsqh"/><path class="jjv4m6b-s"/><path class="fylhtkbms"/><path class="gpgqfdbap"/><path class="a79tt-b_j"/><path class="ep9tu-o-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pagoda-20-bold" /></template>
