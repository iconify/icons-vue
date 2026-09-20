<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebng0rb1m.css';
import '../../css/t/tevsa0mrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebng0rb1m"/><path class="tevsa0mrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:music-square-fill" /></template>
