<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o3b358bfj.css';
import '../../css/q/qw5y-bbmc.css';
import '../../css/d/d8pzfjs5o.css';
import '../../css/q/qqyqacckp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o3b358bfj wm-k"/><path class="qw5y-bbmc wm-a"/><path class="d8pzfjs5o wm-k"/><path class="qqyqacckp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pound-sterling-sketch" /></template>
