<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afeo2fbqa.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGI4v0Oc9U"><path class="afeo2fbqa"/></mask></defs><path mask="url(#SVGI4v0Oc9U)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:square" /></template>
