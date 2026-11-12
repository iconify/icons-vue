<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1e7ksb2s.css';
import '../../css/r/r2xn4m3wh.css';
import '../../css/q/qjfctbrfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c1e7ksb2s"/><path class="r2xn4m3wh"/><circle class="qjfctbrfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rurdesk" /></template>
