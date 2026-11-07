<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo8-9cb-i.css';
import '../../css/q/qsc1wcf4m.css';
import '../../css/b/bhj2g24rh.css';
import '../../css/b/bau2vbc2j.css';
import '../../css/d/dszgb7nxa.css';
import '../../css/h/h0cp9fbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo8-9cb-i"/><path class="qsc1wcf4m"/><path class="bhj2g24rh"/><path class="bau2vbc2j"/><path class="dszgb7nxa"/><path class="h0cp9fbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sleeping-circle-bold-duotone" /></template>
