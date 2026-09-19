<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/c/cyqjerbjs.css';
import '../../css/b/bztzw5bin.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnDF6vd6S"><g class="s9cl3zbei"><path class="cyqjerbjs"/><path class="bztzw5bin"/></g></mask></defs><path mask="url(#SVGnDF6vd6S)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:ranking-list" /></template>
