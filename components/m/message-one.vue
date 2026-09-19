<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/q/qrzpqooux.css';
import '../../css/t/tele8ebjz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnEyzbdTC"><g class="hv130ab-t"><path class="qrzpqooux"/><path class="tele8ebjz"/></g></mask></defs><path mask="url(#SVGnEyzbdTC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:message-one" /></template>
