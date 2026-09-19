<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/t/tjw-xwbxp.css';
import '../../css/d/duhmw1bsi.css';
import '../../css/p/pmzo92h_v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGoAVewbPb"><g class="v3_i3wktz"><path class="tjw-xwbxp"/><rect class="duhmw1bsi"/><rect class="pmzo92h_v"/></g></mask></defs><path mask="url(#SVGoAVewbPb)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:rock-gesture" /></template>
