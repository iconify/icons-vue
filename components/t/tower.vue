<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/m/mpz_0zach.css';
import '../../css/j/j9hg1or3h.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYDbtOuNw"><g class="v3_i3wktz"><path class="mpz_0zach"/><path class="j9hg1or3h"/></g></mask></defs><path mask="url(#SVGYDbtOuNw)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:tower" /></template>
