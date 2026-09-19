<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ue81mlbze.css';
import '../../css/z/zdg9yvbsx.css';
import '../../css/k/k29yudf0l.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdMjhMbPE"><g class="ft5dv1b6b"><path class="ue81mlbze"/><path class="zdg9yvbsx"/><path class="k29yudf0l"/></g></mask></defs><path mask="url(#SVGdMjhMbPE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:signal-strength" /></template>
