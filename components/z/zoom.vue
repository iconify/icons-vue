<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/d/dod3i1bsk.css';
import '../../css/m/mf1jdvbha.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZy0sTdUh"><g class="aql7dnt-u"><path class="dod3i1bsk"/><path class="mf1jdvbha"/></g></mask></defs><path mask="url(#SVGZy0sTdUh)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:zoom" /></template>
