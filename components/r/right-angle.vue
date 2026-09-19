<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-8-qhbnp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGn3H0fbpu"><path clip-rule="evenodd" class="n-8-qhbnp"/></mask></defs><path mask="url(#SVGn3H0fbpu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:right-angle" /></template>
