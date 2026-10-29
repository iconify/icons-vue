<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_0_8kbue.css';
import '../../css/m/mtluovbxd.css';
import '../../css/n/n4zl3ydby.css';
import '../../css/f/f9k1pl6je.css';
import '../../css/z/zvz6ceb7r.css';
import '../../css/d/dwkb1m0vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_0_8kbue wm-shadow"/><path class="mtluovbxd wm-k"/><path class="n4zl3ydby wm-k"/><path class="f9k1pl6je wm-k"/><path class="wm-k zvz6ceb7r"/><path class="dwkb1m0vl wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:trending-up" /></template>
