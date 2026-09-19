<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/y/yktsan6da.css';
import '../../css/i/ip1144q6u.css';
import '../../css/j/jf7ne5b_p.css';
import '../../css/j/jtfatk-pq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtYSFPcqM"><g class="s9cl3zbei"><rect class="yktsan6da"/><path class="ip1144q6u"/><path class="jf7ne5b_p"/><path class="jtfatk-pq"/></g></mask></defs><path mask="url(#SVGtYSFPcqM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:modify-two" /></template>
