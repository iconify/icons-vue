<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pizheebef.css';
import '../../css/u/ui_93yeww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pizheebef"/><path class="ui_93yeww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:play-bold-duotone" /></template>
