<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/k/ky4zetb4b.css';
import '../../css/o/oc2jhta3x.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhjkrxcUE"><g class="s9cl3zbei"><path class="ky4zetb4b"/><path class="oc2jhta3x"/></g></mask></defs><path mask="url(#SVGhjkrxcUE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:medical-box" /></template>
