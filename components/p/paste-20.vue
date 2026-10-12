<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg-os2b_i.css';
import '../../css/z/zyzgsactv.css';
import '../../css/c/c_vkhxzzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xg-os2b_i"/><path class="zyzgsactv"/><path class="c_vkhxzzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paste-20" /></template>
