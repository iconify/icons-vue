<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9a067bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":550,"height":720};
const content = `<path class="a9a067bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:yapcasialogomark" /></template>
