<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-dnevyfw.css';
import '../../css/m/mw0fk06ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-dnevyfw"/><path class="mw0fk06ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:zip-file-check-bold" /></template>
