<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z86v6i08k.css';
import '../../css/u/uf6zebb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="z86v6i08k"/><path class="uf6zebb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yubal-light" /></template>
