<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp7_e5biu.css';
import '../../css/f/foa_mcc1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dp7_e5biu"/><path class="foa_mcc1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sidewaysuppointingindex" /></template>
