<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gy0k7rbbq.css';
import '../../css/b/bqbzmxglo.css';
import '../../css/s/sdpmrcc2s.css';
import '../../css/c/c7ocmjbun.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgZozgdiX"><g class="ft5dv1b6b"><path class="gy0k7rbbq"/><path class="bqbzmxglo"/><path class="sdpmrcc2s"/><path class="c7ocmjbun"/></g></mask></defs><path mask="url(#SVGgZozgdiX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:road-cone" /></template>
