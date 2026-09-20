<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xowad0bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xowad0bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:teamspeak-light" /></template>
