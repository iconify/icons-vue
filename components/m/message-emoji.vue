<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/w/wyv0j7t3c.css';
import '../../css/z/z6dtsjb3m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGi8xqVPZP"><g class="aql7dnt-u"><path class="wyv0j7t3c"/><path class="z6dtsjb3m"/></g></mask></defs><path mask="url(#SVGi8xqVPZP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:message-emoji" /></template>
