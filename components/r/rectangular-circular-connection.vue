<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fobtc1bdc.css';
import '../../css/n/n_jh6lbfx.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZh3QTFPY"><g class="v3_i3wktz"><path class="fobtc1bdc"/><path class="n_jh6lbfx"/></g></mask></defs><path mask="url(#SVGZh3QTFPY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:rectangular-circular-connection" /></template>
