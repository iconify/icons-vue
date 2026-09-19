<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/m/m6ifnhj0n.css';
import '../../css/n/nrx09nbid.css';
import '../../css/k/k1p-s986k.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGiFNxDdbe"><g class="v3_i3wktz"><path class="m6ifnhj0n"/><path class="nrx09nbid"/><path class="k1p-s986k"/></g></mask></defs><path mask="url(#SVGiFNxDdbe)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:male" /></template>
