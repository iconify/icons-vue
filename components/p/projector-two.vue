<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/f/f11w8baut.css';
import '../../css/k/k9mjdebal.css';
import '../../css/g/gvo3tujff.css';
import '../../css/q/qaaxmb3xb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcrCi00JS"><g class="s9cl3zbei"><path class="f11w8baut"/><path class="k9mjdebal"/><path class="gvo3tujff"/><circle class="qaaxmb3xb"/></g></mask></defs><path mask="url(#SVGcrCi00JS)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:projector-two" /></template>
