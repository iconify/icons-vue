<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hde9zom3i.css';
import '../../css/d/di_8scctl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hde9zom3i"/><path class="di_8scctl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:text-size" /></template>
