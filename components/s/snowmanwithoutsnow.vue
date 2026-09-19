<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3y3kybxd.css';
import '../../css/t/tn7efs79w.css';
import '../../css/h/ha95s7gnr.css';
import '../../css/f/fmrf2gbli.css';
import '../../css/q/q-282bbch.css';
import '../../css/y/y01xkg3vz.css';
import '../../css/f/fi5r7hygn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g3y3kybxd"/><path class="tn7efs79w"/><path class="ha95s7gnr"/><path class="fmrf2gbli"/><path class="q-282bbch"/><path class="y01xkg3vz"/><path class="fi5r7hygn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:snowmanwithoutsnow" /></template>
