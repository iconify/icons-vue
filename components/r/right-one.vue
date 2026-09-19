<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp-o-80fw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGoo1xZdsi"><path class="hp-o-80fw"/></mask></defs><path mask="url(#SVGoo1xZdsi)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:right-one" /></template>
