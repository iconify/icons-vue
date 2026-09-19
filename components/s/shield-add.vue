<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/gj7mgbb6o.css';
import '../../css/e/efeuc0qbu.css';
import '../../css/b/bzs_6oz_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="gj7mgbb6o"/><path class="efeuc0qbu"/><path class="bzs_6oz_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:shield-add" /></template>
