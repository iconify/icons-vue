<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/fv9af5lgc.css';
import '../../css/i/i9l44ts8o.css';
import '../../css/a/ac9k9ew8y.css';
import '../../css/q/q9dknlojm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5bXk0bUg"><g class="aql7dnt-u"><path class="fv9af5lgc"/><path class="i9l44ts8o"/><path class="ac9k9ew8y"/><path class="q9dknlojm"/></g></mask></defs><path mask="url(#SVG5bXk0bUg)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:network-tree" /></template>
