<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc2xykbod.css';
import '../../css/z/zid7xkcmh.css';
import '../../css/t/tih4hqb3l.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvF4cycZm"><g class="bc2xykbod"><rect class="zid7xkcmh"/><rect class="tih4hqb3l"/></g></mask></defs><path mask="url(#SVGvF4cycZm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:zero-key" /></template>
