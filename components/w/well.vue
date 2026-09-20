<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw5-8bntt.css';
import '../../css/h/hzh-nhhxi.css';
import '../../css/n/nab94-b5r.css';
import '../../css/s/szdw0lbyi.css';
import '../../css/q/qfvdoibad.css';
import '../../css/g/g2hys0b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw5-8bntt"/><path class="hzh-nhhxi"/><path class="nab94-b5r"/><path class="szdw0lbyi"/><path class="qfvdoibad"/><path class="g2hys0b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:well" /></template>
