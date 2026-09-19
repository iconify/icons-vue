<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/goagzsb5h.css';
import '../../css/h/h9diwtebh.css';
import '../../css/v/vwfxigb9l.css';
import '../../css/e/eftnolbiv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGs5xoxeDs"><g class="ft5dv1b6b"><path class="goagzsb5h"/><rect class="h9diwtebh"/><rect class="vwfxigb9l"/><path class="eftnolbiv"/></g></mask></defs><path mask="url(#SVGs5xoxeDs)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:switch-nintendo" /></template>
