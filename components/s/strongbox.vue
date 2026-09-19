<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a_6h9nbwv.css';
import '../../css/c/cd9fujbkr.css';
import '../../css/u/u581sr0wm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGqPZNEceL"><g class="ft5dv1b6b"><path class="a_6h9nbwv"/><path class="cd9fujbkr"/><path class="u581sr0wm"/></g></mask></defs><path mask="url(#SVGqPZNEceL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:strongbox" /></template>
