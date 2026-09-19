<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/m/m2blynbna.css';
import '../../css/q/q51ei7bew.css';
import '../../css/l/lrrctebji.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnqgV7dAC"><g class="ufeehvblu"><path class="m2blynbna"/><path class="q51ei7bew"/><path class="lrrctebji"/></g></mask></defs><path mask="url(#SVGnqgV7dAC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:trend" /></template>
