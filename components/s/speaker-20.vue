<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs_xbna8j.css';
import '../../css/a/an6ptbjph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xs_xbna8j"/><path class="an6ptbjph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:speaker-20" /></template>
