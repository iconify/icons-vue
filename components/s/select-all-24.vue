<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgp3--bdz.css';
import '../../css/v/v_mxp4bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgp3--bdz"/><path clip-rule="evenodd" class="v_mxp4bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:select-all-24" /></template>
