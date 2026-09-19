<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/g/g60m5abhq.css';
import '../../css/b/bvszfhbhc.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGn4LEfSCA"><g class="aql7dnt-u"><circle class="g60m5abhq"/><path class="bvszfhbhc"/></g></mask></defs><path mask="url(#SVGn4LEfSCA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:mirror-two" /></template>
