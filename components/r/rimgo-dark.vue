<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z15mw-brh.css';
import '../../css/j/jdcotzpev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z15mw-brh"/><circle class="jdcotzpev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rimgo-dark" /></template>
