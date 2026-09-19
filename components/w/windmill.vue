<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enq8bzvvs.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRJXwnbaw"><path clip-rule="evenodd" class="enq8bzvvs"/></mask></defs><path mask="url(#SVGRJXwnbaw)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:windmill" /></template>
