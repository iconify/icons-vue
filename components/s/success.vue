<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/l/l7glbwcru.css';
import '../../css/w/wkfxevblu.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4IxzvcIZ"><g class="aql7dnt-u"><path class="l7glbwcru"/><path class="wkfxevblu"/></g></mask></defs><path mask="url(#SVG4IxzvcIZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:success" /></template>
