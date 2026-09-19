<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/t/tk6mzc_3v.css';
import '../../css/u/uj6jun1kw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGbHv56dcZ"><g class="v3_i3wktz"><path class="tk6mzc_3v"/><path class="uj6jun1kw"/></g></mask></defs><path mask="url(#SVGbHv56dcZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:phone-outgoing-one" /></template>
