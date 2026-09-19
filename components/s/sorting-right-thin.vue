<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnf3cs2wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnf3cs2wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sorting-right-thin" /></template>
