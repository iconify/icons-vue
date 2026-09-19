<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/r/rjhvahbes.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGmWZpVL0o"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="rjhvahbes"/></g></mask></defs><path mask="url(#SVGmWZpVL0o)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:pause-one" /></template>
