<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/o/oc1o0hkfq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGx4eOVcfO"><g class="s9cl3zbei"><path class="oo_vs07_g"/><path class="oc1o0hkfq"/></g></mask></defs><path mask="url(#SVGx4eOVcfO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:voice-one" /></template>
