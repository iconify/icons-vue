<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/ha1kkmb1c.css';
import '../../css/s/svdi4hd7i.css';
import '../../css/h/h9ku_5-7e.css';
import '../../css/f/f6ry3nbeq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG2qMKLc9C"><g class="ft5dv1b6b"><path class="ha1kkmb1c"/><path class="svdi4hd7i"/><path clip-rule="evenodd" class="h9ku_5-7e"/><path class="f6ry3nbeq"/></g></mask></defs><path mask="url(#SVG2qMKLc9C)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:virtual-reality-glasses" /></template>
