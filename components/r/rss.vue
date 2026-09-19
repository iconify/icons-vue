<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxvvz6jiy.css';
import '../../css/c/c_v1vmbxo.css';
import '../../css/k/kev1szbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kxvvz6jiy"/><path class="c_v1vmbxo"/><path class="kev1szbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:rss" /></template>
