<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj208ackd.css';
import '../../css/r/r_67kbawa.css';
import '../../css/q/qlene92hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yj208ackd"/><path class="r_67kbawa"/><path class="qlene92hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-waves-stroke-20" /></template>
