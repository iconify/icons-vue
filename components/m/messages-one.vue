<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1_swcb_o.css';
import '../../css/p/p-3d8dotc.css';
import '../../css/t/t7jhedb5i.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGbExVYPoq"><g class="v1_swcb_o"><path class="p-3d8dotc"/><path class="t7jhedb5i"/></g></mask></defs><path mask="url(#SVGbExVYPoq)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:messages-one" /></template>
