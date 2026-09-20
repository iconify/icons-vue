<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvg3b1btw.css';
import '../../css/i/i_az_4ptl.css';
import '../../css/t/trnnkhiml.css';
import '../../css/m/mm7815c_i.css';
import '../../css/g/g_vunh8kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nvg3b1btw"/><path class="i_az_4ptl"/><path class="trnnkhiml"/><path class="mm7815c_i"/><path class="g_vunh8kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mullvad-vpn" /></template>
