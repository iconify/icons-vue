<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr9bynb9b.css';
import '../../css/g/gxyna80vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hr9bynb9b"/><path class="gxyna80vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:pin-alt-1-fill" /></template>
