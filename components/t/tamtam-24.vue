<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp-rp12lq.css';
import '../../css/r/rx12m6nmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp-rp12lq"/><path clip-rule="evenodd" class="rx12m6nmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:tamtam-24" /></template>
