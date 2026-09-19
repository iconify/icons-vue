<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/co9ks3b9e.css';
import '../../css/e/er9k_1hwx.css';
import '../../css/n/ndry0d1gg.css';
import '../../css/w/w639l80er.css';
import '../../css/p/po5iryr0t.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhJclDCWY"><g class="ft5dv1b6b"><path class="co9ks3b9e"/><path class="er9k_1hwx"/><path class="ndry0d1gg"/><path class="w639l80er"/><circle class="po5iryr0t"/></g></mask></defs><path mask="url(#SVGhJclDCWY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:nuclear-plant" /></template>
