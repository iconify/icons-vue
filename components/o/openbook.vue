<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpl09-boe.css';
import '../../css/m/my7pz4ppw.css';
import '../../css/n/ni4k71_hl.css';
import '../../css/w/w-ic5dfog.css';
import '../../css/z/zzhkhubht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tpl09-boe"/><path class="my7pz4ppw"/><path class="ni4k71_hl"/><path class="w-ic5dfog"/><path class="zzhkhubht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:openbook" /></template>
