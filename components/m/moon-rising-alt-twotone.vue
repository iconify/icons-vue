<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8e22g.css';
import '../../css/w/wh59vr.css';
import '../../css/b/b1urau.css';
import '../../css/u/ubmjts.css';
import '../../css/e/eyuyvm.css';
import '../../css/b/bmy0qq.css';
import '../../css/d/d-k-hl-x.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8e22g wh59vr"/><path class="b1urau s8e22g ubmjts"/><path class="b1urau eyuyvm s8e22g"/><path class="b1urau bmy0qq s8e22g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:moon-rising-alt-twotone" /></template>
