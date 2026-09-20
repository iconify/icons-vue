<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urgyh8mug.css';
import '../../css/g/gx_3x244w.css';
import '../../css/y/y4nqx7dgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urgyh8mug"/><path class="gx_3x244w"/><path class="y4nqx7dgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:spank" /></template>
