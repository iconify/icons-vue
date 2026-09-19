<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2yu2lbpb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOyPzUdDP"><path class="a2yu2lbpb"/></mask></defs><path mask="url(#SVGOyPzUdDP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:sorcerer-hat" /></template>
