<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pgloddc6w.css';
import '../../css/q/q1vdc4fgq.css';
import '../../css/c/cfmnd3hrd.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOt4imOsZ"><g class="ft5dv1b6b"><path class="pgloddc6w"/><path class="q1vdc4fgq"/><circle class="cfmnd3hrd"/></g></mask></defs><path mask="url(#SVGOt4imOsZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:whale" /></template>
