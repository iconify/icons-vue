<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/afeo2fbqa.css';
import '../../css/z/zu2drkjtb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGdCBlela"><g class="ft5dv1b6b"><path class="afeo2fbqa"/><path class="zu2drkjtb"/></g></mask></defs><path mask="url(#SVGGdCBlela)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:tumblr" /></template>
