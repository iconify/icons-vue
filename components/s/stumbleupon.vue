<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3_4cdcfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="a3_4cdcfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:stumbleupon" /></template>
