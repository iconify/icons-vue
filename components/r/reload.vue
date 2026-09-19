<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g44z7fuun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g44z7fuun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:reload" /></template>
