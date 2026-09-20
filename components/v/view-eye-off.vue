<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv2l60z2l.css';
import '../../css/s/sbpa77b-h.css';
import '../../css/o/onghmnteu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv2l60z2l"/><path class="sbpa77b-h"/><path class="onghmnteu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:view-eye-off" /></template>
