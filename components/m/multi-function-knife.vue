<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/m/mm2f4fb5r.css';
import '../../css/g/g9ezxtipi.css';
import '../../css/x/xn3gssb2n.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGosUT5cik"><g class="ufeehvblu"><path class="mm2f4fb5r"/><path class="g9ezxtipi"/><path class="xn3gssb2n"/></g></mask></defs><path mask="url(#SVGosUT5cik)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:multi-function-knife" /></template>
