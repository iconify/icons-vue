<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/m/mz1jqnynl.css';
import '../../css/t/tpn2pebwd.css';
import '../../css/x/xhbx_nbhx.css';
import '../../css/i/ig18oqu2v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdD71QcOE"><g class="aql7dnt-u"><path class="mz1jqnynl"/><path class="tpn2pebwd"/><path class="xhbx_nbhx"/><path class="ig18oqu2v"/></g></mask></defs><path mask="url(#SVGdD71QcOE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:popcorn-one" /></template>
