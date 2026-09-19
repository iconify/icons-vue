<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/r/rf6ic284x.css';
import '../../css/w/w6w67kbba.css';
import '../../css/k/kf2846bit.css';
import '../../css/o/ohbu8jsry.css';
import '../../css/g/gamp7_p1r.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGbt5SmbRn"><g class="s9cl3zbei"><path clip-rule="evenodd" class="rf6ic284x"/><path class="w6w67kbba"/><path class="kf2846bit"/><path class="ohbu8jsry"/><path class="gamp7_p1r"/></g></mask></defs><path mask="url(#SVGbt5SmbRn)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:pesticide" /></template>
