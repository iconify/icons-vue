<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu0j3abrz.css';
import '../../css/p/p-sbw3baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu0j3abrz"/><path clip-rule="evenodd" class="p-sbw3baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:meditation-round-bold" /></template>
