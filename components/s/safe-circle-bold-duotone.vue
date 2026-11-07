<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtmuzrg2o.css';
import '../../css/t/t9ntucclw.css';
import '../../css/v/v81dzmbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtmuzrg2o"/><path clip-rule="evenodd" class="t9ntucclw"/><path class="v81dzmbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-circle-bold-duotone" /></template>
