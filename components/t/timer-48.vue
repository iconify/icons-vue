<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cohfbvw_w.css';
import '../../css/w/ws9mn_3ua.css';
import '../../css/x/xkkhb5coq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cohfbvw_w"/><path class="ws9mn_3ua"/><path class="xkkhb5coq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:timer-48" /></template>
