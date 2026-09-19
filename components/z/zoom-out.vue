<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/e/e-6oifs0n.css';
import '../../css/j/jvput-vek.css';
import '../../css/i/i-8dbccqw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGrYzOtcUx"><g class="ufeehvblu"><path class="e-6oifs0n"/><path class="jvput-vek"/><path class="i-8dbccqw"/></g></mask></defs><path mask="url(#SVGrYzOtcUx)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:zoom-out" /></template>
