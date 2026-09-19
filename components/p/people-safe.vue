<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/c/ccbbnd11y.css';
import '../../css/m/meg_-wbqb.css';
import '../../css/y/ybmshrj6v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnEk6WccL"><g class="v3_i3wktz"><path class="ccbbnd11y"/><circle class="meg_-wbqb"/><path class="ybmshrj6v"/></g></mask></defs><path mask="url(#SVGnEk6WccL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:people-safe" /></template>
