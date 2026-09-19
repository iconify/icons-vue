<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/as2wn2lgv.css';
import '../../css/v/vgah8qb4e.css';
import '../../css/m/maenk-g2f.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlDoIJuob"><g class="ft5dv1b6b"><path class="as2wn2lgv"/><path clip-rule="evenodd" class="vgah8qb4e"/><path class="maenk-g2f"/></g></mask></defs><path mask="url(#SVGlDoIJuob)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:people-minus-one" /></template>
