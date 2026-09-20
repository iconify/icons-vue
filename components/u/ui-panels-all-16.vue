<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfxn6l7fm.css';
import '../../css/z/zvjeae8vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mfxn6l7fm"/><path clip-rule="evenodd" class="zvjeae8vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:ui-panels-all-16" /></template>
