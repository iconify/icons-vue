<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/w/wdquz8zei.css';
import '../../css/a/aewvl6b9u.css';
import '../../css/e/e8-dxttjj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaaefmvJT"><g class="ufeehvblu"><path class="wdquz8zei"/><path class="aewvl6b9u"/><path class="e8-dxttjj"/></g></mask></defs><path mask="url(#SVGaaefmvJT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:sim" /></template>
