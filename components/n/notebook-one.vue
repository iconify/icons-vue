<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/d/drc0ytbts.css';
import '../../css/r/rc1jhvaam.css';
import '../../css/i/i3vo1qb3e.css';
import '../../css/r/r9imp5bbq.css';
import '../../css/q/q65w8gblw.css';
import '../../css/d/dxgqlbbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="drc0ytbts"/><path class="rc1jhvaam"/><path class="i3vo1qb3e"/><path class="r9imp5bbq"/><path class="q65w8gblw"/><path class="dxgqlbbla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:notebook-one" /></template>
