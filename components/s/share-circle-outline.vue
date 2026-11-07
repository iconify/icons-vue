<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cci9ae_nq.css';
import '../../css/o/oexqymb-g.css';
import '../../css/l/lkh3vr24w.css';
import '../../css/z/zcnczmjty.css';
import '../../css/z/zh8221lvv.css';
import '../../css/g/gapgxrbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cci9ae_nq"/><path clip-rule="evenodd" class="oexqymb-g"/><path clip-rule="evenodd" class="lkh3vr24w"/><path class="zcnczmjty"/><path class="zh8221lvv"/><path class="gapgxrbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:share-circle-outline" /></template>
