<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/q/qllazcb1e.css';
import '../../css/c/cl0c6rbvl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDZfZBd9m"><g class="s9cl3zbei"><path clip-rule="evenodd" class="qllazcb1e"/><path class="cl0c6rbvl"/></g></mask></defs><path mask="url(#SVGDZfZBd9m)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:orthopedic" /></template>
