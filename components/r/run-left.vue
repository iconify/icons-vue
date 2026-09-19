<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/k/k9nfxk8un.css';
import '../../css/k/kq3muab2y.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIujexeIo"><g class="aql7dnt-u"><path class="k9nfxk8un"/><path class="kq3muab2y"/></g></mask></defs><path mask="url(#SVGIujexeIo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:run-left" /></template>
