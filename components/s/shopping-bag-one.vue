<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0a9vkbzg.css';
import '../../css/g/g_w3_soty.css';
import '../../css/g/g3guvac8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="a0a9vkbzg"><rect class="g_w3_soty"/><path class="g3guvac8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:shopping-bag-one" /></template>
