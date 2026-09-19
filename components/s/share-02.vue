<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/yw_2a4n5f.css';
import '../../css/m/ma4nqdb6e.css';
import '../../css/p/p1e355btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="yw_2a4n5f"/><circle class="ma4nqdb6e"/><circle class="p1e355btg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:share-02" /></template>
