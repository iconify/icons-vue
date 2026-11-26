<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/u/umg9mabsh.css';
import '../../css/p/p89spcbxn.css';
import '../../css/c/cnjmpob5b.css';
import '../../css/v/v0w8swbtc.css';
import '../../css/c/cvrcvob3i.css';
import '../../css/a/aof1lbhol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><radialGradient id="SVGk8dSCbwd" cx="46.1" cy="38.4" r="102.5" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset=".85" class="umg9mabsh"/><stop offset="1" class="umg9mabsh"/></radialGradient></defs><path class="p89spcbxn"/><path fill="url(#SVGk8dSCbwd)" transform="matrix(2.8 0 0 2.8 -28.016 -28.016)" class="cnjmpob5b"/><path class="v0w8swbtc"/><path class="cvrcvob3i"/><path class="aof1lbhol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:white-small-square" /></template>
