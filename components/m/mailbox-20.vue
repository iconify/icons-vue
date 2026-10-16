<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxp96ub2p.css';
import '../../css/z/zcyb7gkkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qxp96ub2p"/><path class="zcyb7gkkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mailbox-20" /></template>
