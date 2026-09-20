<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4pkyxbyo.css';
import '../../css/j/j34xgl0mc.css';
import '../../css/h/hti6_g1vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="q4pkyxbyo"/><circle class="j34xgl0mc"/><circle class="hti6_g1vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:smlight-dark" /></template>
