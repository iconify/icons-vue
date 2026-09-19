<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/p/pjw4h4wuo.css';
import '../../css/r/rt1h_-mxc.css';
import '../../css/h/hsxkkdbde.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAVOXMIBC"><g class="ufeehvblu"><path class="pjw4h4wuo"/><path class="rt1h_-mxc"/><path class="hsxkkdbde"/></g></mask></defs><path mask="url(#SVGAVOXMIBC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:shake" /></template>
