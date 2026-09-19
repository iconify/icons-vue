<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgga7abld.css';
import '../../css/s/si50jvboo.css';
import '../../css/k/k-gfreizg.css';
import '../../css/f/f0elirbsr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8Z0dpeyP"><g class="cgga7abld"><path class="si50jvboo"/><path class="k-gfreizg"/><path class="f0elirbsr"/></g></mask></defs><path mask="url(#SVG8Z0dpeyP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:skiing-nordic" /></template>
