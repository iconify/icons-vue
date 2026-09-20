<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_byzp5sk.css';
import '../../css/g/gj4pehvxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j_byzp5sk"/><path clip-rule="evenodd" class="gj4pehvxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:navigation-arrow-off-solid" /></template>
