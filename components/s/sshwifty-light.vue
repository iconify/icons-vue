<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8rbiiblu.css';
import '../../css/w/w_gkkwbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b8rbiiblu"/><path class="w_gkkwbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sshwifty-light" /></template>
