<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/k/ka1_8zbxt.css';
import '../../css/o/ooj06lbbu.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVPrCLdYG"><g class="aql7dnt-u"><path class="ka1_8zbxt"/><path class="ooj06lbbu"/></g></mask></defs><path mask="url(#SVGVPrCLdYG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:rotation-one" /></template>
