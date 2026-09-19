<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/msv6_bc6s.css';
import '../../css/e/eowf-ngqj.css';
import '../../css/s/s89v55brw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcXNH2dMl"><g class="s9cl3zbei"><path class="msv6_bc6s"/><path class="eowf-ngqj"/><path class="s89v55brw"/></g></mask></defs><path mask="url(#SVGcXNH2dMl)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:seo-folder" /></template>
