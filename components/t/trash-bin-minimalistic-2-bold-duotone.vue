<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pepyl3vpw.css';
import '../../css/z/z3n43-bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pepyl3vpw"/><path class="z3n43-bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:trash-bin-minimalistic-2-bold-duotone" /></template>
