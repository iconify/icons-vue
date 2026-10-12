<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqaun74ep.css';
import '../../css/g/gv61adbwm.css';
import '../../css/p/pqeizzbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqaun74ep"/><path clip-rule="evenodd" class="gv61adbwm"/><path class="pqeizzbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-pin-house-filled" /></template>
