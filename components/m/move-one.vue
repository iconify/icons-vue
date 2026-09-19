<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6gxxwbzy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3aodzdrj"><path class="v6gxxwbzy"/></mask></defs><path mask="url(#SVG3aodzdrj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:move-one" /></template>
