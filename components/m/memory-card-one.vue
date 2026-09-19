<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/z/zfnvhzb9k.css';
import '../../css/m/m30ctoxuq.css';
import '../../css/h/hpzp4y6qo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxOwcE7Mo"><g class="v3_i3wktz"><path class="zfnvhzb9k"/><path class="m30ctoxuq"/><path class="hpzp4y6qo"/></g></mask></defs><path mask="url(#SVGxOwcE7Mo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:memory-card-one" /></template>
