<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/d/dzhl58nwn.css';
import '../../css/w/wk8bg5zve.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLQsOGbhf"><g class="aql7dnt-u"><rect class="dzhl58nwn"/><path class="wk8bg5zve"/></g></mask></defs><path mask="url(#SVGLQsOGbhf)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:table" /></template>
