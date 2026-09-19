<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lodgmg-3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lodgmg-3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-subtract-alt-filled" /></template>
