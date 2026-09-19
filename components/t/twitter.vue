<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md3_ln_5j.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWg8t6c8U"><path class="md3_ln_5j"/></mask></defs><path mask="url(#SVGWg8t6c8U)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:twitter" /></template>
