<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hdd5oubow.css';
import '../../css/j/jo17i5bnz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMulGzc6e"><g class="ft5dv1b6b"><path class="hdd5oubow"/><path class="jo17i5bnz"/></g></mask></defs><path mask="url(#SVGMulGzc6e)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:sun-one" /></template>
