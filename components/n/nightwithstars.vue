<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvuwh_b1o.css';
import '../../css/s/sco41b1mo.css';
import '../../css/k/ku0gyybci.css';
import '../../css/b/b72jh0c6g.css';
import '../../css/o/orrftzb-f.css';
import '../../css/f/f0745kbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tvuwh_b1o"/><path class="sco41b1mo"/><path class="ku0gyybci"/><path class="b72jh0c6g"/><path class="orrftzb-f"/><path class="f0745kbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:nightwithstars" /></template>
