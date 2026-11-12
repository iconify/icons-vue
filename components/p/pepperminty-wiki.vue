<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkophvw2v.css';
import '../../css/l/lib909ajt.css';
import '../../css/s/stui2mbih.css';
import '../../css/d/dty293bfj.css';
import '../../css/i/iycln-b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="pkophvw2v"/><path class="lib909ajt"/><radialGradient id="SVGuHMPpV7u" cx="256" cy="256" r="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".806" class="stui2mbih"/><stop offset="1" class="dty293bfj"/></radialGradient><circle fill="url(#SVGuHMPpV7u)" class="iycln-b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pepperminty-wiki" /></template>
