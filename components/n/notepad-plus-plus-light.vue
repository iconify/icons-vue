<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_q0t1ebv.css';
import '../../css/o/o5xttwudf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c_q0t1ebv"/><path class="o5xttwudf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notepad-plus-plus-light" /></template>
