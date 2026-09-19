<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/i/i52zvrbop.css';
import '../../css/y/yhpmvvbra.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGviwhKdRv"><g class="v3_i3wktz"><path class="i52zvrbop"/><path class="yhpmvvbra"/></g></mask></defs><path mask="url(#SVGviwhKdRv)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:rectangular-circular-separation" /></template>
