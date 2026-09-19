<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/y/ykbumoigx.css';
import '../../css/k/kqqgs194l.css';
import '../../css/m/mlwciqb2o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpF3UGe0r"><g class="s9cl3zbei"><path class="ykbumoigx"/><path class="kqqgs194l"/><path class="mlwciqb2o"/></g></mask></defs><path mask="url(#SVGpF3UGe0r)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:viewfinder" /></template>
