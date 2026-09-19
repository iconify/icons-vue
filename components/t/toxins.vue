<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g-g8_3lxs.css';
import '../../css/i/ioqq5abex.css';
import '../../css/f/fsoi-q3pn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzvgk7cVf"><g class="ufeehvblu"><path clip-rule="evenodd" class="g-g8_3lxs"/><path class="ioqq5abex"/><path class="fsoi-q3pn"/></g></mask></defs><path mask="url(#SVGzvgk7cVf)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:toxins" /></template>
