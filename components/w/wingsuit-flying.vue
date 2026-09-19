<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgga7abld.css';
import '../../css/s/si50jvboo.css';
import '../../css/b/bf_msp58c.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhNHrpdRn"><g class="cgga7abld"><path class="si50jvboo"/><path class="bf_msp58c"/></g></mask></defs><path mask="url(#SVGhNHrpdRn)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:wingsuit-flying" /></template>
