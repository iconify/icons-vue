<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzoimlb-v.css';
import '../../css/p/pemqbc__o.css';
import '../../css/p/p3q4orbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wzoimlb-v"/><path class="pemqbc__o"/><path class="p3q4orbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:passkey-20" /></template>
