<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/u/uns4e8bmd.css';
import '../../css/u/uo9qgzmqh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4Rm6Hdox"><g class="aql7dnt-u"><path class="uns4e8bmd"/><path class="uo9qgzmqh"/></g></mask></defs><path mask="url(#SVG4Rm6Hdox)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:weixin-top-stories" /></template>
