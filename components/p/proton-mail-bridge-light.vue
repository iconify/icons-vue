<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aph_dqbwx.css';
import '../../css/r/rulnoebmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aph_dqbwx"/><path class="rulnoebmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-mail-bridge-light" /></template>
