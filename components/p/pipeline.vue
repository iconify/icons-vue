<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_1mwj-2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_1mwj-2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:pipeline" /></template>
