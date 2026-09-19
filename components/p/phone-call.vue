<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/qe0g46bxg.css';
import '../../css/e/euxi43hbo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWVRuoepI"><g class="v3_i3wktz"><path class="qe0g46bxg"/><path class="euxi43hbo"/></g></mask></defs><path mask="url(#SVGWVRuoepI)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:phone-call" /></template>
