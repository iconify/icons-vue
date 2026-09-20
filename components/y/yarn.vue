<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqplhccxe.css';
import '../../css/m/m597sacji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":518,"height":518};
const content = `<path class="kqplhccxe"/><path class="m597sacji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:yarn" /></template>
