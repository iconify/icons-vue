<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/f/f7orvpbwy.css';
import '../../css/i/i9aqj_b9h.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGL6k8IccK"><g class="ufeehvblu"><path class="f7orvpbwy"/><path class="i9aqj_b9h"/></g></mask></defs><path mask="url(#SVGL6k8IccK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:platte" /></template>
