<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luulaebmy.css';
import '../../css/a/a7mffllux.css';
import '../../css/f/fk2bfybvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="luulaebmy"/><path class="a7mffllux"/><path class="fk2bfybvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:pill" /></template>
