<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5fk6_dbl.css';
import '../../css/x/x1i1gufdc.css';
import '../../css/r/r-mx-gbyo.css';
import '../../css/a/az8fldb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGKawXkcgx" x1="256" x2="256" y1="14.357" y2="497.643" gradientUnits="userSpaceOnUse"><stop offset="0" class="k5fk6_dbl"/><stop offset="1" class="x1i1gufdc"/></linearGradient><path fill="url(#SVGKawXkcgx)" class="r-mx-gbyo"/><path class="az8fldb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-onenote-2013" /></template>
