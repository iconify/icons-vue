<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyd8q7b-w.css';
import '../../css/x/x4db5135n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyd8q7b-w"/><path class="x4db5135n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:play-forward-duotone" /></template>
