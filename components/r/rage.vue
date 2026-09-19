<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gshe_di8n.css';
import '../../css/t/tcsfyac_a.css';
import '../../css/f/fb_ijtbgm.css';
import '../../css/z/z7iigyukn.css';
import '../../css/w/wlzju0bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gshe_di8n"/><path class="tcsfyac_a"/><path class="fb_ijtbgm"/><path class="z7iigyukn"/><path class="wlzju0bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:rage" /></template>
