<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/p/p8o4yhfax.css';
import '../../css/d/dpzr-imtn.css';
import '../../css/j/j7omkubgn.css';
import '../../css/g/gga-wp10j.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3CNQqcrc"><g class="ufeehvblu"><path class="p8o4yhfax"/><path class="dpzr-imtn"/><path class="j7omkubgn"/><path class="gga-wp10j"/></g></mask></defs><path mask="url(#SVG3CNQqcrc)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:petrol" /></template>
