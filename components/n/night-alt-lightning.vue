<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue4blbbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="ue4blbbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:night-alt-lightning" /></template>
