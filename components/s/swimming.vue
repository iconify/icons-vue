<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veir1qbiz.css';
import '../../css/a/a5u582bgm.css';
import '../../css/g/gy7khnb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="veir1qbiz"/><circle class="a5u582bgm"/><path class="gy7khnb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:swimming" /></template>
