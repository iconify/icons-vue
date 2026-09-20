<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn0_nldrm.css';
import '../../css/m/mxu_p1jge.css';
import '../../css/p/p6xe6zmnr.css';
import '../../css/c/c0lvt3b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hn0_nldrm"/><path class="mxu_p1jge"/><path class="p6xe6zmnr"/><path class="c0lvt3b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vmware-workstation-pro" /></template>
