<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lvwaq0byj.css';
import '../../css/o/opbtt0byp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzSbqXbqj"><g class="ufeehvblu"><path class="lvwaq0byj"/><path class="opbtt0byp"/></g></mask></defs><path mask="url(#SVGzSbqXbqj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:shield-add" /></template>
