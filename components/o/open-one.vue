<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/m/mf4kxbb7i.css';
import '../../css/q/qp5l2y6-o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzIoW9KLC"><g class="aql7dnt-u"><path class="mf4kxbb7i"/><circle class="qp5l2y6-o"/></g></mask></defs><path mask="url(#SVGzIoW9KLC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:open-one" /></template>
