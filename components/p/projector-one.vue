<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r14ef2_yx.css';
import '../../css/j/jqkefvlhn.css';
import '../../css/n/n5a1vkb0v.css';
import '../../css/x/xhl55ccgo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaMV5ubEy"><g class="ft5dv1b6b"><path class="r14ef2_yx"/><rect class="jqkefvlhn"/><rect class="n5a1vkb0v"/><path class="xhl55ccgo"/></g></mask></defs><path mask="url(#SVGaMV5ubEy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:projector-one" /></template>
