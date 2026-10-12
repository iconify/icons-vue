<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gng09bdfn.css';
import '../../css/d/dyii5ab_p.css';
import '../../css/x/xwm12jb_o.css';
import '../../css/f/f1aa_zbes.css';
import '../../css/l/lzmnrrp8b.css';
import '../../css/m/mxz5qbb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gng09bdfn"/><path class="dyii5ab_p"/><path class="xwm12jb_o"/><path class="f1aa_zbes"/><path class="lzmnrrp8b"/><path class="mxz5qbb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-meter-x-20" /></template>
