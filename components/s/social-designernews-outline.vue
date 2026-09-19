<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho0-29b5y.css';
import '../../css/v/vhbe095-l.css';
import '../../css/x/xa-305ipw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ho0-29b5y"/><path class="vhbe095-l"/><path class="xa-305ipw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-designernews-outline" /></template>
