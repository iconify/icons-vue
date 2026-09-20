<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b37ujtb-g.css';
import '../../css/u/u9y__jw4b.css';
import '../../css/e/eej59_rhy.css';
import '../../css/z/zujjfbcsh.css';
import '../../css/x/xbfqloslf.css';
import '../../css/v/v3vlycc2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b37ujtb-g"/><path class="u9y__jw4b"/><path class="eej59_rhy"/><path class="zujjfbcsh"/><path class="xbfqloslf"/><path class="v3vlycc2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-tiles" /></template>
