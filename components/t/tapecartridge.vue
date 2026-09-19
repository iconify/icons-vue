<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxj0albai.css';
import '../../css/c/cx5wjlbpv.css';
import '../../css/c/cylan_37t.css';
import '../../css/j/juzjijckv.css';
import '../../css/z/zd-u8obhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zxj0albai"/><path class="cx5wjlbpv"/><path class="cylan_37t"/><circle class="juzjijckv"/><path class="zd-u8obhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:tapecartridge" /></template>
