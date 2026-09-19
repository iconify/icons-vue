<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6c8tmzid.css';
import '../../css/f/f8eyw1sna.css';
import '../../css/u/u1jc8vaze.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9PaAjcIO"><g class="t6c8tmzid"><path class="f8eyw1sna"/><path class="u1jc8vaze"/></g></mask></defs><path mask="url(#SVG9PaAjcIO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:phone-two" /></template>
