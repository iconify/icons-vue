<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/l/lsk5ggfzs.css';
import '../../css/l/l23-6lzft.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIgrD9mmM"><g class="aql7dnt-u"><path clip-rule="evenodd" class="lsk5ggfzs"/><path class="l23-6lzft"/></g></mask></defs><path mask="url(#SVGIgrD9mmM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:water-rate-two" /></template>
