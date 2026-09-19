<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/q/qnx6idjmr.css';
import '../../css/w/wgbgurmsp.css';
import '../../css/h/hgrrm0nzr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkQ0mucVk"><g class="hv130ab-t"><path class="qnx6idjmr"/><path class="wgbgurmsp"/><path class="hgrrm0nzr"/></g></mask></defs><path mask="url(#SVGkQ0mucVk)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:prison" /></template>
