<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2_bfiwax.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtHWbAZui"><path class="a2_bfiwax"/></mask></defs><path mask="url(#SVGtHWbAZui)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:mitsubishi" /></template>
