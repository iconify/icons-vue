<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th3k4si2y.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOOU2tccc"><path class="th3k4si2y"/></mask></defs><path mask="url(#SVGOOU2tccc)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:ulikecam" /></template>
