<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/n/necufhi6r.css';
import '../../css/x/xuaiitbah.css';
import '../../css/c/cmjkozb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="necufhi6r"/><rect transform="matrix(1 0 0 -1 4.5 19.5)" class="xuaiitbah"/><rect transform="matrix(1 0 0 -1 6 15.5)" class="cmjkozb_n"/><rect transform="matrix(1 0 0 -1 16 15.5)" class="cmjkozb_n"/><rect transform="matrix(1 0 0 -1 11 15.5)" class="cmjkozb_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:pantheon-outline" /></template>
