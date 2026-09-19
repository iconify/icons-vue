<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/c/cac4-p7tm.css';
import '../../css/a/asipl7e6a.css';
import '../../css/b/b0j8rmbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="cac4-p7tm"/><path class="asipl7e6a"/><path class="b0j8rmbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:volume-up-thin" /></template>
