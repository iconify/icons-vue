<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhfn9yzfo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYCI0xe9j"><path class="jhfn9yzfo"/></mask></defs><path mask="url(#SVGYCI0xe9j)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:right-two" /></template>
