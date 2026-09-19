<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/c/c8jtaacin.css';
import '../../css/l/l9oi_4b2p.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBrQMxecJ"><g class="wwvp95byt"><path class="c8jtaacin"/><path class="l9oi_4b2p"/></g></mask></defs><path mask="url(#SVGBrQMxecJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:message-sent" /></template>
