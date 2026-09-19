<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpl_e0shw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7auVBcPn"><path class="rpl_e0shw"/></mask></defs><path mask="url(#SVG7auVBcPn)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:system" /></template>
