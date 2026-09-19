<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_8qphb1a.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCOhucbsT"><path class="n_8qphb1a"/></mask></defs><path mask="url(#SVGCOhucbsT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:quadrilateral" /></template>
