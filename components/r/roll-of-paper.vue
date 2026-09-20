<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsyi_mb5r.css';
import '../../css/i/ig-y-fydf.css';
import '../../css/d/dyyf6jb2c.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/z/zip4qmbvb.css';
import '../../css/a/ax6vmbcnm.css';
import '../../css/n/nyqbdaclh.css';
import '../../css/x/xynmdcbfx.css';
import '../../css/b/bkz9njz-x.css';
import '../../css/c/c8_2mybww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="hsyi_mb5r"/><path class="ig-y-fydf"/><ellipse class="dyyf6jb2c"/><g class="brzn_0bpr"><ellipse class="zip4qmbvb"/><path class="ax6vmbcnm"/><path class="nyqbdaclh"/><path class="xynmdcbfx"/><path class="bkz9njz-x"/><ellipse class="c8_2mybww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:roll-of-paper" /></template>
