<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y379_3lgr.css';
import '../../css/o/o774rzb4z.css';
import '../../css/x/xd1z83qkw.css';
import '../../css/v/vygt9fbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y379_3lgr"/><path class="o774rzb4z"/><path class="xd1z83qkw"/><path class="vygt9fbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:socialhome" /></template>
