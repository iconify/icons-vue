<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q92_u99ez.css';
import '../../css/c/cwtinvbzw.css';
import '../../css/q/qwjuf14gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q92_u99ez"/><path class="cwtinvbzw"/><path clip-rule="evenodd" class="qwjuf14gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-up-outline" /></template>
