<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opnfa-u8z.css';
import '../../css/n/n80hob-xf.css';
import '../../css/z/zx64x75sx.css';
import '../../css/z/zv8n_eywr.css';
import '../../css/k/k978evhme.css';
import '../../css/t/tt5d1s3ih.css';
import '../../css/m/mrk8m9bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="opnfa-u8z"/><path class="n80hob-xf"/><path class="zx64x75sx"/><path class="zv8n_eywr"/><path class="k978evhme"/><path class="tt5d1s3ih"/><path class="mrk8m9bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-access-2018-light" /></template>
