<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/i/i1yn_n3se.css';
import '../../css/s/sr2ovzbeo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMMH8wrHj"><g class="aql7dnt-u"><path class="i1yn_n3se"/><path class="sr2ovzbeo"/></g></mask></defs><path mask="url(#SVGMMH8wrHj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:video-conference" /></template>
