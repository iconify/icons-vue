<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqo72weep.css';
import '../../css/h/h339_5zrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pqo72weep"/><path class="h339_5zrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:rc" /></template>
