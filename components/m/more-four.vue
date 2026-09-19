<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8-c1m0ua.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG1RrlacnE"><path class="k8-c1m0ua"/></mask></defs><path mask="url(#SVG1RrlacnE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:more-four" /></template>
