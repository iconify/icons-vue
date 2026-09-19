<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/b/b8tqzsb4n.css';
import '../../css/z/zsvlx-b6c.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtC5EwcvX"><g class="aql7dnt-u"><path class="b8tqzsb4n"/><path class="zsvlx-b6c"/></g></mask></defs><path mask="url(#SVGtC5EwcvX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:voice-input" /></template>
