<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vprg18qvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":290,"height":79};
const content = `<path clip-rule="evenodd" class="vprg18qvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:polygon-io" /></template>
