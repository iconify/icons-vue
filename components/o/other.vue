<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/p/pqn0aix0g.css';
import '../../css/l/lw-duqbbf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGEldDdqf"><g class="s9cl3zbei"><path class="pqn0aix0g"/><path class="lw-duqbbf"/></g></mask></defs><path mask="url(#SVGGEldDdqf)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:other" /></template>
