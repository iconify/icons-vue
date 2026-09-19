<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/k/k1ji6-3eq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVHlBKdjS"><g class="aql7dnt-u"><rect class="h9qj9o6mz"/><path class="k1ji6-3eq"/></g></mask></defs><path mask="url(#SVGVHlBKdjS)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:one-key" /></template>
