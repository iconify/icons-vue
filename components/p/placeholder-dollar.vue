<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbxwgrbol.css';
import '../../css/p/pyk3d0bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="qbxwgrbol"/><path clip-rule="evenodd" class="pyk3d0bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:placeholder-dollar" /></template>
