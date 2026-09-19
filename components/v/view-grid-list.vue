<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/d/dn-6osbwv.css';
import '../../css/p/pyd589bxf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3vuoSZSm"><g class="v3_i3wktz"><rect class="h9qj9o6mz"/><path class="dn-6osbwv"/><path class="pyd589bxf"/></g></mask></defs><path mask="url(#SVG3vuoSZSm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:view-grid-list" /></template>
