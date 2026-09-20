<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr-alcbvt.css';
import '../../css/z/z2347ac7w.css';
import '../../css/m/mn75_48em.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tr-alcbvt"/><path class="z2347ac7w"/><path class="mn75_48em"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sc" /></template>
