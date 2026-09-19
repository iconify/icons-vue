<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fqzg-n1xw.css';
import '../../css/i/ixe451mff.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZeL81xTZ"><g class="v3_i3wktz"><path class="fqzg-n1xw"/><path class="ixe451mff"/></g></mask></defs><path mask="url(#SVGZeL81xTZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:pay-code" /></template>
