<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6xxsw.css';
import '../../css/s/s8e22g.css';
import '../../css/b/b1urau.css';
import '../../css/z/zac2_x.css';
import '../../css/n/npdh_t.css';
import '../../css/c/chf8aj.css';
import '../../css/s/so-from-56.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6xxsw s8e22g"/><path class="b1urau s8e22g zac2_x"/><path class="b1urau npdh_t s8e22g"/><path class="b1urau chf8aj s8e22g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:moon-alt-filled" /></template>
