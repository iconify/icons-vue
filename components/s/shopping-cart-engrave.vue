<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f19a-bbhg.css';
import '../../css/k/k60dwsbzs.css';
import '../../css/w/wjvpugbbq.css';
import '../../css/y/ytznpnb1t.css';
import '../../css/e/euee9wbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f19a-bbhg wm-k"/><path class="k60dwsbzs wm-a"/><path class="wjvpugbbq wm-shadow"/><path class="wm-k ytznpnb1t"/><path class="euee9wbaf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shopping-cart-engrave" /></template>
