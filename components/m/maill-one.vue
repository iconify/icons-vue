<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m2blynbna.css';
import '../../css/o/o2ir8p9au.css';
import '../../css/k/k4pywfg3u.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGr4wA8dyJ"><g class="s9cl3zbei"><path class="m2blynbna"/><path class="o2ir8p9au"/><path class="k4pywfg3u"/></g></mask></defs><path mask="url(#SVGr4wA8dyJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:maill-one" /></template>
