<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/s/s9v3gsb7k.css';
import '../../css/x/xd7hlgbdq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtwAIUclL"><g class="aql7dnt-u"><path class="s9v3gsb7k"/><path class="xd7hlgbdq"/></g></mask></defs><path mask="url(#SVGtwAIUclL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:pennant" /></template>
