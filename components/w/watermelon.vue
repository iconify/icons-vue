<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/k/ktokpccng.css';
import '../../css/r/rtdu8kbun.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6EkOAb1c"><g class="ufeehvblu"><path class="ktokpccng"/><path class="rtdu8kbun"/></g></mask></defs><path mask="url(#SVG6EkOAb1c)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:watermelon" /></template>
