<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl11e_b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zl11e_b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:test-tube-rack" /></template>
