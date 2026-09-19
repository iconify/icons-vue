<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/e/etjiufbjy.css';
import '../../css/u/uioyaxcnw.css';
import '../../css/d/dfq1qtbfg.css';
import '../../css/s/s94jr3b8f.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIbA3leUh"><g class="s9cl3zbei"><path class="etjiufbjy"/><path class="uioyaxcnw"/><path class="dfq1qtbfg"/><path class="s94jr3b8f"/></g></mask></defs><path mask="url(#SVGIbA3leUh)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:reverse-lens" /></template>
