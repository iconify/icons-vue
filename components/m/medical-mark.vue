<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/w/wonky8b2c.css';
import '../../css/f/fskaxzzpg.css';
import '../../css/k/kinc7xbvh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwoSM3bAQ"><g class="ufeehvblu"><path class="wonky8b2c"/><path class="fskaxzzpg"/><path class="kinc7xbvh"/></g></mask></defs><path mask="url(#SVGwoSM3bAQ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:medical-mark" /></template>
