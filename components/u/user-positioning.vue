<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/q/qni966bju.css';
import '../../css/c/c96bn9bfp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDAWLkdts"><g class="aql7dnt-u"><circle class="qni966bju"/><path class="c96bn9bfp"/></g></mask></defs><path mask="url(#SVGDAWLkdts)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:user-positioning" /></template>
