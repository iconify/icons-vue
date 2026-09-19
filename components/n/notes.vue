<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/w/wqt01gb2m.css';
import '../../css/u/uouile4nz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHfF3VcIU"><g class="ufeehvblu"><path class="wqt01gb2m"/><path class="uouile4nz"/></g></mask></defs><path mask="url(#SVGHfF3VcIU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:notes" /></template>
