<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/o/o2sblwhlm.css';
import '../../css/t/tg712obfr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGyLGssdZJ"><g class="aql7dnt-u"><path clip-rule="evenodd" class="o2sblwhlm"/><path class="tg712obfr"/></g></mask></defs><path mask="url(#SVGyLGssdZJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:tea-drink" /></template>
